---
title: "Uma rotina metodológica para reconstrução 3D e extração de parâmetros geométricos de edificações em baixo nível de detalhamento a partir de dado LiDAR aerotransportado"
venue: "Simpósio Brasileiro de Sensoriamento Remoto (SBSR), Santos, 2017"
date: 2017-05-29
classes: wide
layout: archive
gallery2:
  - url: /assets/images/papers/sbsr-2017/1/class-build-ground-veg.png
    image_path: assets/images/papers/sbsr-2017/1/class-build-ground-veg.png
    alt: "Some of the outcomes through the methodology stages. Point cloud classified by ground, low and high vegetation, and buildings. The first picture presents all classes"
gallery3:
  - url: /assets/images/papers/sbsr-2017/1/3d-models.png
    image_path: assets/images/papers/sbsr-2017/1/3d-models.png
    alt: "Recife, PE, Brazil, Digital elevation Models. (left) Digital Surface Model (DSM). (center) Digital Terrain Model (DTM). (right) Normalized Digital Surface Model (nDSM)"
gallery4:
  - url: /assets/images/papers/sbsr-2017/1/3d-buildings-all.png
    image_path: assets/images/papers/sbsr-2017/1/3d-buildings-all.png
    alt: "Buildings in 3D, extruded only from elevation and roof-footprints"
categories:
  - proceedings
tags:
  - 3d-reconstruction
  - city
  - lidar
  - lastools    
---
<span style="color:lightblue">**Rodolfo G. Lotte**</span>, Edison A. Mitishita, and Cláudia M. de Almeida

[<i class='fas fa-file-download'></i> Download paper]({{site.baseurl}}/assets/files/publications/sbsr-2017/1/galoa-proceedings--sbsr-60075-uma-rotina-metod.pdf){: .btn .btn--danger}
[<i class='fas fa-file-download'></i> Download poster]({{site.baseurl}}/assets/files/publications/sbsr-2017/1/poster-1.pdf){: .btn .btn--success}

Abstract
=======
<h-abstract>To understand the principles of an organized urban environment requires the analysis of structural relationships between objects and shapes contained in it. Establish limits of implementation and inappropriate regions growth requires an understanding of its many variations and levels of detail, opening in this way, more accurate alternative to the administration of large cities. Over the years, much effort and progress has been made in the characterization of objects with the advent of remote sensing, by using multispectral, hyperspectral, microwave, among others types of information. More recently, in mid-2004, a new way of imaging, laser sensors enriches the target information by acquiring not only spectral information, but also geometric. In Brazil, due to the richness and abundance of vegetation, the use of structural information has been continuously employed in the forestry sector, such as biomass estimates, characterization of tree species, agriculture and its various aspects, among other. In the urban sector, however, few studies have been carried out, either by lack of data and complete surveys, or the interest of public sectors. three dimensional (3D) building models, generated both from laser sensors as photogrammetric, called structural data, when performed on a large scale, allow a better understanding of geometrical aspects such as form, volume, space occupation and possible environmental impacts. In urban areas, the study of shadows cast by buildings, identification of heat islands, thermal comfort, realistic navigation, tourism, entertainment, urban planning, traffic control, surveillance of irregular buildings, update territorial databases or information of urban trees are examples of areas supported by the use of semantic systems, generated by 3D data analysis. From a given LiDAR airborne data, this work presents a methodological routine for 3D reconstruction of urban space at a low level of detail and, therefore, estimate geometric parameters such as shape, area, volume, location, and height.</h-abstract>

**Info!** Dear researcher/scientist/academic, you may find some Wikipedia references in this page, which are totally directed for those that might not be familiar with terms and need a more illustrative and didatical understanding. Please, fell free to contribute at any moment. 
{: .notice--warning}

Contextualization
=======

{% include gallery id="gallery2" caption="Some of the outcomes through the methodology stages. Point cloud classified by ground, low and high vegetation, and buildings. The first picture presents all classes" %}

{% include gallery id="gallery3" caption="Recife, PE, Brazil, Digital elevation Models. (left) Digital Surface Model (DSM). (center) Digital Terrain Model (DTM). (right) Normalized Digital Surface Model (nDSM)" %}

{% include gallery id="gallery4" caption="Buildings in 3D, extruded only from elevation and roof-footprints" %}

Source-code and tools
======
The tools and source-code was mainly made in LAStools, which a set of scripts were used to classify the Recife-PE LiDAR point cloud. Golden Surfer was used for graphing and layout purposes. For documentation, the LaTeX and Kile editor were used. Below, each tool is presented as an icon, together with its frequency of use.

**Coding:**

| ![alt-LAStools]({{site.baseurl}}/assets/images/logo/same-dim/lastools.png?style=centerme) | 
|:--:|
| LAStools | 
|:--:|
|<i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i>|

**IDE:**

| ![alt-SurferPyCharm]({{site.baseurl}}/assets/images/logo/same-dim/surfer.png?style=centerme) | 
|:--:|
| Surfer |
|:--:|
|<i class="fa fa-ellipsis-h" style="color:#50ff00"></i><i class="fa fa-ellipsis-h" style="color:#50ff00"></i><i class="fa fa-ellipsis-h" style="color:#50ff00"></i><i class="fa fa-ellipsis-h" style="color:#50ff00"></i><i class="fa fa-ellipsis-h" style="color:#454D5B"></i>|

**Arts:**

| ![alt-Adobe Illustrator]({{site.baseurl}}/assets/images/logo/same-dim/illustrator.png?style=centerme) | ![alt-Adobe Photoshop]({{site.baseurl}}/assets/images/logo/same-dim/photoshop.png?style=centerme) | ![alt-Adobe InDesign]({{site.baseurl}}/assets/images/logo/same-dim/indesign.png?style=centerme) |
|:--:|:--:|:--:|
| Illustrator | Photoshop | InDesign |
|:--:|:--:|:--:|
|<i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i>|<i class="fa fa-ellipsis-h" style="color:orange"></i><i class="fa fa-ellipsis-h" style="color:orange"></i><i class="fa fa-ellipsis-h" style="color:#454D5B"></i><i class="fa fa-ellipsis-h" style="color:#454D5B"></i><i class="fa fa-ellipsis-h" style="color:#454D5B"></i>|<i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i>|

**Documentation:**

| ![alt-Kile]({{site.baseurl}}/assets/images/logo/same-dim/kile.png?style=centerme) | ![alt-LaTeX]({{site.baseurl}}/assets/images/logo/same-dim/tex.png?style=centerme) |
|:--:|:--:|
| Kile | LaTeX |
|:--:|:--:|
|<i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i>|<i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i><i class="fa fa-ellipsis-h" style="color:#00bfff"></i>|

Presentation
======
![image-left]({{site.baseurl}}/assets/images/papers/sbsr-2017/1/poster-2017-thumb.png){: .align-left} This work has been presented in a poster form (left), during the [National Remote Sensing Symposium (SBSR)](www.sbsr.com.br/), hosted by the National Institute for Space Research (INPE), in Santos, 2017. The poster can be download in the green buttom at the top of this page.

<!-- For this presentation, we summarized the stages since the raw SAR image until the delineation of the roads network by the use of Active Contour, which is initializated by points recognized by Self-Organized Maps.

Still, the results show the difficult on the application of Snakes over too noisy images. The model should to include a weight that would aldo take into account the speckle noisy, which would allow to compensate the evolution on the energy function minimization.  -->

Cite this paper
======
```latex
@InProceedings{lotte2017a,
  author     = {Rodolfo G. Lotte; Cl\'audia M de Almeida; and Edison A. Mitishita},
  title      = {Uma rotina metodol\'ogica para reconstru{\c c}\~ao {3D} e extra{\c c}\~ao de par\^ametros geom\'etricos 
  de edifica{\c c}\~aes em baixo n\'ivel de detalhamento a partir de dado LiDAR aerotransportado},
  booktitle  = {Anais do XVIII Simp\'osio Brasileiro de Sensoriamento Remoto (SBSR)},
  year       = {2017},
  date       = {22/05/2017},
  eventtitle = {SIMP\'OSIO BRASILEIRO DE SENSORIAMENTO REMOTO},
  volume     = {18},
  publisher  = {INPE},
  isbn       = {978-85-17-00088-1},
  pages      = {7819-7826},
  url        = {http://urlib.net/8JMKD3MGP6W34M/3PSMGFJ},
}
```