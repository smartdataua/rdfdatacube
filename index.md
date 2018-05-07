## Introduction
Today,  most  organisations  using  Open  Data  are  focused on  data  processing  and  analysis.  Services  provided  are  for
instance  the  transformation  of  raw  data  into  actionable insights.  However,  regarding  the  reuse  of  Open  Data,  there
is  a  lot  of  work  to  be  done  to  exploit  its  full potential.

This example is based on datasets from [Open Data Barcelona](http://opendata-ajuntament.barcelona.cat/es/).

### RDF Data Cube W3C

The  [RDF  Data  Cube  vocabulary](https://www.w3.org/TR/vocab-data-cube/) is  a  W3C  recommendation  for  the  publication  of
multi-dimensional  data  on  the  web,  such  as  statistics.  In particular,  it  defines  the  dimensions,  attributes  and  measures used  in  the  dataset  and  it  builds  upon  existing  RDF vocabularies  (for  example  SKOS,  SCOVO,  Dublin  Core,
FOAF,  etc.).

### Cubeviz.js

[CubeViz](https://github.com/AKSW/cubevizjs) is utilizing the RDF Data Cube vocabulary which is the state-of-the-art in representing statistical data in Resource Description Framework (RDF). This vocabulary is compatible with SDMX and increasingly being adopted. Based on the vocabulary and the encoded Data Cube, CubeViz is generating a faceted browsing widget that can be used to filter interactively observations to be visualized in charts. Based on the selected structure, CubeViz offer beneficiary chart types and options which can be selected by users.

### Example

This is an example of how to publish data data which could help re-users to understand how the city’s open datasets could be used  in a meaningful way. The example is based on a [multidimensional dataset](ttps://raw.githubusercontent.com/hibernator11/datacuberdf/master/rdf-02-2017.n3). 

<iframe width="100%" height="300" src="//jsfiddle.net/gcandela/gv84Lthn/1/embedded/result/" allowpaymentrequest allowfullscreen="allowfullscreen" frameborder="0"></iframe>


