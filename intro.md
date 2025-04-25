---
title: AI for Climate Tutorial
authors:
    - name: Peter Sadowski
      affiliations:
        - id: uhcs
          institution: University of Hawaii Manoa
          department: Information and Computer Sciences
          city: Honolulu
          website: https://peterjsadowski.github.io
        - Information and Computer Sciences # A hack
    - name: Gerardo Rivera Tello
      affiliations:
        - id: uhatmo
          institution: University of Hawaii Manoa
          department: Atmospheric Sciences
          city: Honolulu
          website: https://griverat.github.io
        - Atmospheric Sciences # A hack

---

# Welcome 

This workshop introduces climate applications of artificial intelligence (AI) and machine learning (ML). The first part will provide an overview of some different applications. The second part will be a tutorial with hands-on examples. The examples are chosen to build participants' intuition for AI uses in weather and climate modeling while still being small enough to run on a laptop or [Google Colab](https://colab.research.google.com).  

# Outline

1. Presentation on applications of AI for climate
1. Tutorial: training AI models in Pytorch for computer vision.
1. Tutorial: predicting ENSO with AI
1. Tutorial: predicting SST with AI


For this workshop we will use NOAA's sea surface temperature (SST) data [](#fig:sst_daily). We will be analyzing the monthly SST anomaly from historical means.

% A figure of an image with a caption.
:::{figure} https://psl.noaa.gov/map/images/sst/sst.daily.gif
:label: fig:sst_daily

Today's sea surface temperature, courtesy of [NOAA](https://psl.noaa.gov/map/clim/sst.shtml).
:::


% An admonition containing a note
:::{note}
This tutorial uses _real_ data, but the data has been processed down to size that can be downloaded quickly for the examples given here. The data processing code is included in a separate section so that you can reproduce it if needed. 
:::


%If you sold 100 books at \$10 per book, you'd have \$1000 dollars according to [](#eq:book). If instead you publish your Jupyter Book to the web for free, you'd have \$0 dollars!
% An arbitrary math equation
%:::{math}
%:name: eq:book
%x \times y = z
%:::


# Learning Outcomes

1. Familiarity with common applications of ML in climate and weather modeling
1. Familiarity with challenges of applying ML 
1. Understanding the basics of probabilistic ML
1. Experience training deep neural network models in Pytorch
1. Experience with model evaluation and model selection

# Prerequisites

- Familiarity with Python
- Python environment with Numpy, Pytorch, Matplotlib installed 


