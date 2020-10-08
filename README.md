# GRNN-Flu-Cases
Repository for the Graph Recurrent Neural Networks Project on analysis of Flu cases in New York

Graph Recurrent Neural Networks (GRNNs) are a way of doing Machine Learning. More specifically, the Gated GRNNs are useful when what we want to predict is a sequence of data in a given network, and where an earlier data point can determine or influence a very later data point, be it in a spatial or temporal way.

In this project, first we reproduced the results of many experiments involving different kinds of Graph Neural Networks to test their performance with artificial data generated with code changing the dependencies and information enclosed on the data.

We also developed our own experiment where we used the traffic data of the counties in New York and the flu cases reported at different weeks of the year 2010 and 2011 in all those counties. By combining those two insights (traffic and flu cases) we were able to implement a Graph Recurrent Neural Network to predict the cases in later weeks. In the beginning the error was very high, but after tuning the parameters of the network (a very important part of the very iterative process of working with Neural Networks) we could bring the error down considerably.

Apart from epidemics, this kind of experiments can be escalated and applied to other areas and problems, so it becomes relevant to different fields and situations.

You can consult the research poster and video on https://presentations.curf.upenn.edu/poster/gated-graph-recurrent-neural-networks

We used the previous work of Fernando Gama https://github.com/alelab-upenn/graph-neural-networks for the GNN library creation, and Luana Ruiz https://github.com/luanaruiz9/gated_gcrnns for the adaptation to use the library on Graph Recurrent Neural Networks.

Made with the Sponsorship of the Penn Unergraduate Research Mentoring Program under the mentorship of Alejandro Ribeiro and Luana Ruiz

Created by Ricardo Del Rio and Mariana Luna
