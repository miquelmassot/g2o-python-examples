# g2o-python-examples

This repository contains examples of g2o-python on GraphSLAM, optimisation and bundle adjustment

## Requisites

Install `g2o-python` as

```bash
pip install g2o-python
```

## Concepts

In g2o, poses are represented as vertices in a graph. In the figure, they are $\left\lbrace x_1, x_2, x_3, x_4, x_5 \right\rbrace$. The edges that join these vertices are odometric measurements. 

Landmarks (or features, observations) are represented as a different type of vertices and its corresponding measurement is encoded in the edge that joins a pose vertex to the landmark vertex. These are $\left\lbrace z_1, z_2, z_3 \right\rbrace$ in the figure.

![example g2o image](https://www.plantuml.com/plantuml/png/RP5D2eCm44RtSuhikfAId-n4l4SfOZNLW9gIJY5u-iOsmLd4rUDx3nb8-yRUusTT02wBUI93nxoTPcIZzMP0wpP0zphcXqDqAzdZTs2_JOjXWRCRr6kFSnCwNbz_17TQ25A8OY598Ok58eKg5feK-YnWi7w8VZ_lt3jUy89uKV2IU4byuApoLSE2W20IIWWoeOAW4kf_NCLROff19iYJo5C4bI1J_AzE0AtPnlX-Nm00)
