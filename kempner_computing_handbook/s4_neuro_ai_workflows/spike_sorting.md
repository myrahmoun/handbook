# Spike Sorting

Spike sorting is the classification and identification of action potentials from extracellular electrophysiological recordings for the purpose of discriminating spikes from different neurons. It involves filtering raw signals, spike detection, feature extraction of waveforms, and clustering them into distinct neuronal units. Accurate sorting is essential for the study of neural coding and circuit dynamics but is difficult due to waveform overlap, electrode drift, and noise. Developments in machine and computational learning methods are improving its scalability and accuracy and rendering it increasingly possible for large-scale neural recordings in systems neuroscience.

![SegmentLocal](figures/gif/spikes.gif "segment")

<div style="text-align: center; font-size: 12px; max-width: 600px; margin: 0 auto;">
Raw voltage traces for extracellular recordings.
<p>Image credit: <a href="https://yliapis.github.io/A-Classical-Approach-to-Spike-Sorting/" target="_blank">Y. Liapis, A Classical Approach to Spike Sorting</a>.</p>
</div>

In collaboration with the [Allen Institute](https://alleninstitute.org/), the Kempner Research and Engineering team developed spike sorting pipelines to support researchers on the [FASRC](https://www.rc.fas.harvard.edu/) Cannon and [HMS RC](https://it.hms.harvard.edu/about/departments/research-computing) O2 computing clusters.

In order to utilize these pipelines for your spike sorting project on either computer cluster, follow the instructions below.

[Steps to run the spike sorting pipeline on the FASRC Cannon Cluster at FAS](https://github.com/KempnerInstitute/ephys-spike-sorting/tree/main/pipeline/kempner_cluster)
  
[Steps to run the spike sorting pipeline on the O2 Cluster at HMS](https://github.com/KempnerInstitute/ephys-spike-sorting/tree/main/pipeline/hms_cluster)



