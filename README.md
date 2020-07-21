# Faster-RCNN
State-of-the-art object detection networks depend on region proposal algorithms to hypothesize object
locations. Advances like SPPnet and Fast R-CNN have reduced the running time of these detection
networks, exposing region proposal computation as a bottleneck. Hence, Fatser RCNN improves upon
that by introducing Regional Proposal Network (RPN), that shares full-image convolutional features
with the detection network, thus enabling nearly cost-free region proposals.

This is an benchmark implementation of Faster-RCNN using RESNET-50 fpn backbone and pretrained on COCO dataset. 
