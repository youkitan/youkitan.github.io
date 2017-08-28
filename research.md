---
layout: page
title: "Research"
alt_title: ""
sub_title: "Scopes to scanners: connecting research one synapse at a time"
paginate: true
image: /assets/images/research2.png

---
Broadly speaking, my research interests can be captured by three questions: 1) does it combine ideas or methods from multiple disciplines? 2) does it help me towards my goal of understanding curiosity, or intrinsic motivation? 3) does it help improve the way people can do research?

---

<br>
### Principled decoding of hippocampal replay
<a href="{{site.url}}/assets/images/poster.pdf"><img hspace="10" vspace="10" style="float:right; padding-left:10px;" src="{{site.url}}/assets/images/replay.svg" alt="Alt Text" ></a>
Hippocampal place cell activity forms internally generated sequences called “replays” that represent spatiotemporal trajectories during periods of rest or quiesence. There is much current interest in decoding the content of these sequences, in order to access the contents of memory retrieval, consolidation and planning. However, because these sequences are covert phenomena (i.e., without observable behavior) it is unclear how a principled approach to decoding these sequences can be made in the absence of ground truth. We can approach this problem in two ways. The first is to [optimize decoding for generalization performance and quantify the effect or parameter choice and biases in the input data on decoding accuracy](http://www.biorxiv.org/content/biorxiv/early/2017/01/24/066670.full.pdf). The second is to develop a generative model of hippocampal replay and establish a suite of population level statistical measures. To the extent that the model generated data is a good description of experimental data at the population level, the simulated data can then be used to determine how to best approach decoding the (now known) ground truth<sup>1</sup>.
<br><br>

---

<br>
<div style="text-align: right"><h3> Influence of motivational states on the content of replay </h3></div>

<a href="{{site.url}}"><img hspace="10" vspace="10" style="border-radius:35px; float:left; padding-right:10px;" src="{{site.url}}/assets/images/maze.jpg" alt="Alt Text" ></a>
What we traditionally consider to be "place cells" have been shown to carry information about direction<sup>2</sup>, speed<sup>3</sup>, odors<sup>4</sup>, and various contextual cues pertaining to the environment or task<sup>5,6</sup>. Furthermore, it has also been shown that the hippocampus is required for using internally generated cues such as the appetitive state of the animal to make correct inferences in a non-spatial contextual retrieval task<sup>7</sup>. If the internal motivational state of the animal can drive behavior in such a way, it could be that the actual encoding of spatial representations are altered by these states. Some evidence exists suggesting that the content of both online and offline spatial representations<sup>8,9</sup> are modulated in this way. Following work from preivous students in the lab, I'm interested in understanding what is the relationship between motivational state and the way internal representations are shaped and used. To this end, I am currently testing rats in a motivational shift paradigm with a plus maze. Looking forward, I am interested in exploring if can we distinguish how external vs internal motivation shape the way spaces are represented in hippocampus and whether the prospective content of internally generated sequences depend on these different kinds of motivational states. 
<br><br>

---

<br>
### Geometry of hippocampal representations

<a href="http://hypertools.readthedocs.io/en/latest/"><img hspace="10" style="border-radius:35px; float:right; padding-left:10px;" src="{{site.url}}/assets/images/hyperalign.png" alt="Alt Text" ></a>
Finding new ways to think about data and discovering tools to probe different kinds of questions is a valuable aspect of discovery driven work. A major component of my graduate work has thus been developing new computational tools to analyze electrophysiological data. I love learning new computational methods and am lucky enough to be exposed to the many trades of the tool in human neuroimaging in our department here at Dartmouth. One such approach is to think about time series of neural data as trajectories through a neural space and actually visualize this trajectory. Instead of focusing on single cell responses, this way we can capture the dynamics of ensemble activity and understand the structure these dynamics in a visually intuitive way much like how the traditional "tuning curve" opened a way of thinking about neural response. Using these kinds of tools, I'm interested in developing a common platform for thinking about neural data whether it is single cell recordings in rodents or fMRI data collected from humans.
<br><br>

---

<font size="2">
<ol style="text-align: left">
	<li>Johnson, A., Fenton, A. a., Kentros, C., & Redish, a. D. (2009). Looking for cognition in the structure within the noise. Trends in Cognitive Sciences, 13(2), 55–64. 
	<a href="http://doi.org/10.1016/j.tics.2008.11.005">[DOI link]</a></li>
	<li>Navratilova, Z., Hoang, L. T., Schwindel, C. D., Tatsuno, M., & McNaughton, B. L. (2012). Experience-dependent firing rate remapping generates directional selectivity in hippocampal place cells. Frontiers in Neural Circuits, 6 (February), 1–14. 
	<a href="http://doi.org/10.3389/fncir.2012.00006">[DOI link]</a></li>
	<li>Huxter, J., Burgess, N., & O’Keefe, J. (2003). Independent rate and temporal coding in hippocampal pyramidal cells. Nature, 425(6960), 828–832. <a href="http://doi.org/10.1038/nature02058">[DOI link]</a></li>
	<li>Anderson, M. I., & Jeffery, K. J. (2003). Heterogeneous modulation of place cell firing by changes in context. The Journal of Neuroscience : The Official Journal of the Society for Neuroscience, 23(26), 8827–8835. 
	<a href="http://doi.org/23/26/8827">[DOI link]</a></li>
	<li>Leutgeb, S., Leutgeb, J. K., Barnes, C. A., Moser, E. I., McNaughton, B. L., & Moser, M.-B. (2005). Independent Codes for Spatial and Episodic Memory in Hippocampal Neuronal Ensembles, (July), 619–623. 
	<a href="http://doi.org/10.1126/science.1114037">[DOI link]</a></li>
	<li>Allen, K., Rawlins, J. N. P., Bannerman, D. M., & Csicsvari, J. (2012). Hippocampal Place Cells Can Encode Multiple Trial-Dependent Features through Rate Remapping. J Neurosci, 32(42), 14752–14766. 
	<a href="http://doi.org/10.1523/JNEUROSCI.6175-11.2012">[DOI link]</a></li>
	<li>Kennedy, P. J., & Shapiro, M. L. (2004). Retrieving Memories via Internal Context Requires the Hippocampus. Journal of Neuroscience, 24(31), 6979–6985. 
	<a href="http://doi.org/10.1523/JNEUROSCI.1388-04.2004">[DOI link]</a></li>
	<li>Kennedy, P. J., & Shapiro, M. L. (2009). Motivational states activate distinct hippocampal representations to guide goal-directed behaviors. Proceedings of the National Academy of Sciences of the United States of America, 106(26), 10805–10. 
	<a href="http://doi.org/10.1073/pnas.0903259106">[DOI link]</a></li>
	<li>Carey, A. A. (2014). Does motivational state affec the content of hippocampal replay? Theses and Dissertations. University of Waterloo. 
	<a href="https://uwspace.uwaterloo.ca/handle/10012/9539">[LINK]</a></li>
</ol> 
</font>


<!-- 

actions:
	- label: "home"
	icon: home
	url: index.html

	- label: "about"
	icon: user
	url: about.html

	- label: "&nbsp;&nbsp;&nbsp;fun"
	icon: gamepad
	url: "fun.html"

	- label: "cv"
	icon: university
	url: "cv.html"

 -->





