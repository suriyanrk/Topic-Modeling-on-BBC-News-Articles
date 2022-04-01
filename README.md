# Topic-Modeling-on-BBC-News-Articles
Extraction/identification of major topics &amp; themes discussed in news articles
# <b><u> Project Title : Extraction/identification of major topics & themes discussed in news articles. </u></b>

## <b> Problem Description </b>

### Project objective is to identify major themes/topics across a collection of BBC news articles.

----

## <b> Data Description </b>

### The dataset contains a set of news articles for each major segment consisting of business, entertainment, politics, sports and technology. You need to create an aggregate dataset of all the news articles and perform topic modeling on this dataset. Verify whether these topics correspond to the different tags available.

# LDA
Latent: This refers to everything that we don’t know in prior and are hidden in the data. Here, the themes or topics that document consists of are unknown, but they are believed to be present as the text is generated based on those topics.\

Dirichlet: It is a ‘probablity of distributions’. Yes, you read it right. But what does this mean? Let’s think about this with the help of an example. Let’s suppose there is a machine that produces dice and we can control whether the machine will always produce a dice with equal weight to all sides, or will there be any bias for some sides. So, the machine producing dice is a distribution as it is producing dice of different types. Also, we know that the dice itself is a distribution as we get multiple values when we roll a dice. This is what it means to be a distribution of distributions and this is what Dirichlet is. Here, in the context of topic modeling, the Dirichlet is the distribution of topics in documents and distribution of words in the topic. It might not be very clear at this point of time, but it’s fine as we will look at it in more detail in a while.
Allocation: This means that once we have Dirichlet, we will allocate topics to the documents and words of the document to topics.
# References
1. Topic modelling, wikipedia.org- https://en.wikipedia.org/wiki/Topic_model#:~:text=In%20machine%20learning%20and%20natural,structures%20in%20a%20text%20body.
2. Analytical Vidya- https://towardsdatascience.com/topic-modeling-and-latent-dirichlet-allocation-in-python-9bf156893c24
