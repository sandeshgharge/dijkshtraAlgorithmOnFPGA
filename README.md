# DijkshtraAlgorithmFPGA

## Aim
The goal of our project is to implement Dijkstra Algorithm on FPGA. Post implementation we will see how FPGA performs in comparison with CPU.

## Overview
The Dijkstra Algorithm is a pre-defined algorithm conceived by computer scientist Edward W. Dijkstra. This algorithm helps find the shortest distance between two points in a given graph. FPGA (Field Programmable Gate Arrays) are semiconductor devices based around a matrix of configurable logic blocks (CLBs) connected via programmable interconnects. To briefly explain, FPGA is known for parallel computing, unlike normal CPUs. We are curious to know if the Dijkstra Algorithm works better on FPGA than CPU. While running this project we will compare the time taken by FPGA and CPU on Jupyter Notebook for further conclusions.

# Folder structure

All the presentation files (.pdf and .ppt) are placed under folder PresentationDocuments

IP .cpp Files are placed under folder IPFiles

# Steps :

1. Copy DijkstraFPGA.ipynb, dijkshtra.bit, dijkshtra.hwh, dijkshtra.tcl file to Pynq Board.
2. Run DijkstraFPGA.ipynb till end for required output.
