# Visualizing online communities on social media
## MozFest 2022 Exhibit

{% include mozfest_graph_viz.html %}

In the MozFest Trustworthy AI Working Group's project on visualizing communities and subcultures on social media, we set out to create a visualization that captured the dynamic time dependence of interactions between communities on the Internet. The visualization above is a proof-of-concept of the kinds of dynamics and interactions that can be captured using a graph visualization. We focus on two COVID-related hashtags that parent groups have been using on Twitter - `#teamreality` and `#urgencyofnormal`. Each node represents a hashtag, and each edge represents the two connected hashtags apprearing in the same Tweet, with the frequency of how often the appear signified by the color and width of the edge. You can use the slider to see the time dependence of this co-occurence.

To see how the data was retrieved and the visualization was created, see [this notebook](https://github.com/twitterdev/hashtag-graph-viz/blob/main/notebooks/hashtag_graph_example_from_tweets.ipynb)


Visualization created by:
- [Mia Feng](https://twitter.com/mia_mifeng)
- [Dina Mistry](https://twitter.com/dinacmistry)
- [Nico Gendron](https://twitter.com/nico_gendron)
- [Kristian Lum](https://twitter.com/KLdivergence)
- [Tomo Lazovich](https://twitter.com/laughsovich)

with special thanks to the working group participants:
- Bhargavi Ganesh
- Srividya Suresh
- Rawan Omar Gaafar
- Dharvi Verma
- Juliana Novaes
- Borhane Blili-Hamelin
- Unnati Patel
- Stef Garasto
- Giulio Valentino Dalla Riva
- Rhiannon Bettivia
- Mo Johnson-León
- Michael Sampson
- Navdeep Gill
