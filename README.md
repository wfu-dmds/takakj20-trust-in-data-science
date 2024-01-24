# Trust in Data Science

* Need to be more explicit about what we mean when we say "re-write the paragraph" - maybe give examples for extremes for each of the principles
* https://www.tandfonline.com/doi/full/10.1080/10618600.2022.2104290
  
## Prompt for GPT

There are six principles of data analysis: 
data matching: How well does the available data match the data needed to investigate a question?
exhaustive: Are specific questions addressed using multiple, complementary methods, tooling or workflows?
skeptical: Are multiple, related explanations considered using the same data?
second-order: Does the analysis include anything that does not directly address the primary question, but gives important context to the analysis?
clarity: Does the analysis summarize data in a way that is influential in explaining how the underlying data connects to the conclusions?
reproducible: Could someone who is not the original producer take the published code and data and compute the same results?

Use the dataset below to fill in for a, b, and c.


# make sure to update to the right principles that match our study
A reader weights the principles as follows: 
data matching: a
exhaustive: b
skeptical: c

``` r
library(tidyverse); expand_grid(a=1:5, b=1:5, c=1:5) |> print(n = 125)
#> # A tibble: 125 × 3
#>         a     b     c
#>     <int> <int> <int>
#>   1     1     1     1
#>   2     1     1     2
#>   3     1     1     3
#>   4     1     1     4
#>   5     1     1     5
#>   6     1     2     1
#>   7     1     2     2
#>   8     1     2     3
#>   9     1     2     4
#>  10     1     2     5
#>  11     1     3     1
#>  12     1     3     2
#>  13     1     3     3
#>  14     1     3     4
#>  15     1     3     5
#>  16     1     4     1
#>  17     1     4     2
#>  18     1     4     3
#>  19     1     4     4
#>  20     1     4     5
#>  21     1     5     1
#>  22     1     5     2
#>  23     1     5     3
#>  24     1     5     4
#>  25     1     5     5
#>  26     2     1     1
#>  27     2     1     2
#>  28     2     1     3
#>  29     2     1     4
#>  30     2     1     5
#>  31     2     2     1
#>  32     2     2     2
#>  33     2     2     3
#>  34     2     2     4
#>  35     2     2     5
#>  36     2     3     1
#>  37     2     3     2
#>  38     2     3     3
#>  39     2     3     4
#>  40     2     3     5
#>  41     2     4     1
#>  42     2     4     2
#>  43     2     4     3
#>  44     2     4     4
#>  45     2     4     5
#>  46     2     5     1
#>  47     2     5     2
#>  48     2     5     3
#>  49     2     5     4
#>  50     2     5     5
#>  51     3     1     1
#>  52     3     1     2
#>  53     3     1     3
#>  54     3     1     4
#>  55     3     1     5
#>  56     3     2     1
#>  57     3     2     2
#>  58     3     2     3
#>  59     3     2     4
#>  60     3     2     5
#>  61     3     3     1
#>  62     3     3     2
#>  63     3     3     3
#>  64     3     3     4
#>  65     3     3     5
#>  66     3     4     1
#>  67     3     4     2
#>  68     3     4     3
#>  69     3     4     4
#>  70     3     4     5
#>  71     3     5     1
#>  72     3     5     2
#>  73     3     5     3
#>  74     3     5     4
#>  75     3     5     5
#>  76     4     1     1
#>  77     4     1     2
#>  78     4     1     3
#>  79     4     1     4
#>  80     4     1     5
#>  81     4     2     1
#>  82     4     2     2
#>  83     4     2     3
#>  84     4     2     4
#>  85     4     2     5
#>  86     4     3     1
#>  87     4     3     2
#>  88     4     3     3
#>  89     4     3     4
#>  90     4     3     5
#>  91     4     4     1
#>  92     4     4     2
#>  93     4     4     3
#>  94     4     4     4
#>  95     4     4     5
#>  96     4     5     1
#>  97     4     5     2
#>  98     4     5     3
#>  99     4     5     4
#> 100     4     5     5
#> 101     5     1     1
#> 102     5     1     2
#> 103     5     1     3
#> 104     5     1     4
#> 105     5     1     5
#> 106     5     2     1
#> 107     5     2     2
#> 108     5     2     3
#> 109     5     2     4
#> 110     5     2     5
#> 111     5     3     1
#> 112     5     3     2
#> 113     5     3     3
#> 114     5     3     4
#> 115     5     3     5
#> 116     5     4     1
#> 117     5     4     2
#> 118     5     4     3
#> 119     5     4     4
#> 120     5     4     5
#> 121     5     5     1
#> 122     5     5     2
#> 123     5     5     3
#> 124     5     5     4
#> 125     5     5     5
```

Rewrite the following paragraph with the readers principle weights in mind based on the columns in the dataset. Add this paragraph in a new column, d and output the results:

A clip of a newspaper article is being written for someone who has specific expectations of principles of data analysis in terms of how they weight the importance of each. Here are the details for the article: 

Broken Skin Barriers are Causing an Increase in Food Allergies by Bryan Thomas

A possible reason that the prevalence of food allergies has increased from less than 1% of the population to almost 6% of the US population in 40 years is because of broken skin barriers. When new food is introduced topically on skin, if the skin barrier is disrupted, the immune system views this food as an intruder. Then later on, when the food is eaten, the body’s immune system reacts the same way, seeing the food as an intruder. Thus, children with eczema, and other skin conditions, are at higher risk for developing food allergies. Because of this reasoning, in 2017, the National Institute of Allergy and Infectious Diseases updated its guidelines on how to introduce peanuts, the leading allergen in the US, to infants with eczema.

According to the National Eczema Association, about 10.1% of the U.S. population has some form of eczema and the prevalence of childhood atopic dermatitis increased for 8% to 15% since 1997.

We interviewed Dr. Waheeda Samady, Associate Professor of Pediatrics at Northwestern University Feinberg School of Medicine. She is a board certified Pediatrician with a medical degree from University of California, along with a fellowship and residency in pediatrics at the same university. Her specialty is in Hospital-Based Medicine and she has been published on eight papers, one specifically on egg allergies in children (another leading allergen in the United States).
## Possible Survey Paragraph
Broken Skin Barriers are Causing an Increase in Food Allergies by Bryan Thomas

A possible reason that the prevalence of food allergies has increased from less than 1% of the population to almost 6% of the US population in 40 years is because of broken skin barriers. When new food is introduced topically on skin, if the skin barrier is disrupted, the immune system views this food as an intruder. Then later on, when the food is eaten, the body’s immune system reacts the same way, seeing the food as an intruder. Thus, children with eczema, and other skin conditions, are at higher risk for developing food allergies. Because of this reasoning, in 2017, the National Institute of Allergy and Infectious Diseases updated its guidelines on how to introduce peanuts, the leading allergen in the US, to infants with eczema. According to the National Eczema Association, about 10.1% of the U.S. population has some form of eczema and the prevalence of childhood atopic dermatitis increased for 8% to 15% since 1997.

We interviewed Dr. Avery Lewis, a board certified pediatric allergist at the Mayo Clinic.Duke University Hospital. Dr. Lewis earned his undergraduate degree from Duke University and proceeded to attend Duke University School of Medicine, where he earned his medical degree. He also did his residency and fellowship at the Mayo Clinic. His speciality is hospital based medicine and has published nine papers, three focused on allergy prevention in early childhood development.



## Week 3 

* We are proposing doing a two-phase study, in the first phase participants will see a paragraph about some quantitiative analysis with components about the data, the analysis, and the analyst. We will ask them overall whether they find the analysis believable and then will ask them to highlight portions of the text and rank the selection as making the overall information more or less believable
  
List below ideas for a paragraph to show participants in Phase 1 of our study

Overall ideas: neutral, relevant topics in health 
Elements: data, anaylysis, the analyst

- https://www.npr.org/2023/09/12/1199159009/a-popular-nasal-decongestant-doesnt-actually-relieve-congestion-fda-advisers-say
- advise about over the counter medication use and its actual effectiveness
- https://www.npr.org/2023/09/06/1198013055/what-to-know-about-the-link-between-air-pollution-and-superbugs
- how worse illnesses and air pollution are connected
- https://www.npr.org/sections/goatsandsoda/2023/09/03/1197197648/we-asked-you-answered-share-an-encounter-with-a-stranger-that-lifted-your-spirit
- how saying hello to anyone or thing can bring you happiness
- https://www.npr.org/2023/08/31/1196986907/have-a-food-allergy-your-broken-skin-barrier-might-be-to-blame
- link between food allergies and a poor skin barrier


## Week 1 & 2 Summary

I reviewed the 28 articles that Dr. McGowan selected and evaluated each abstract to decide if the focus was on data visualization, data analysis, both, or another topic. From there, I decided if they seemed related to our possible research, which lead to me reading about 11 articles. There were a few similar to our goal, either centered around machine learning, with a high level of base knowledge needed, or AI and trusting its output. There were also many articles that focused on what factors will help increase trust and what discrease trust, although between studies, the results were contradictory. In dicussion with Dr. McGowan, we talked through conducted a two phase study, where in the first phase, participatns will a paragraph on some anaylisis of data with information about the analysis and even the analyst. Then we will ask them to select portions of the paragraph and select if the information highlighted made the information believeable.
