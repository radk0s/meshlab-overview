# Meshlab Overview
 	
MeshLab - http://meshlab.sourceforge.net/ ~15k lines

The Visualization and Computer Graphics Library  - http://vcg.isti.cnr.it/vcglib/ ~ 100k lines

Features
* Interactive selection and deletion of portion of the mesh. Even for large models.
* Painting interface for selecting, smoothing and coloring meshes.

Input/output in many formats:

* import:PLY, STL, OFF, OBJ, 3DS, COLLADA, PTX, V3D, PTS, APTS, XYZ, GTS, TRI, ASC, X3D, X3DV, VRML, ALN
* export:PLY, STL, OFF, OBJ, 3DS, COLLADA, VRML, DXF, GTS, U3D, IDTF, X3D
* Point Clouds support. Now 3D files that are composed only by points are well supported in PLY and OBJ format.
* U3D support; MeshLab is the first open source tool to provide direct conversion of 3D meshes into the U3D format. * Now you can create pdf, like this with 3D objects with just MeshLab and LaTeX.

Mesh Cleaning Filters:

* removal of duplicated, unreferenced vertices, null faces
* removal of small isolated components
* coherent normal unification and flipping
* erasing of non manifold faces
* automatic filling of holes

Remeshing filters:

* High quality edge collapse simplification (even with texture coords preservation)
* Surface reconstruction from points (a ball pivoting variant, marching cubes and poisson's reconstruction)
* Subdivision surfaces (loop and butterfly)
* Feature preserving smoothing and fairing filters
* Holes filling

Various Colorization/Inspection filters

* Gaussian and mean curvature
* Border edges, geodesic distance, from borders
* Non two-manifold edges and vertices
* Self intersecting faces
* Ambient Occlusion. An ambient occlusion field can be computed and stored per vertex

Interactive Mesh Painting
* Color Painting
* Selection paint
* Smoothing

Measuring tool. You can take linear measures between points of the displayed meshes
Slicing tool. A new tool that allows to export planar sections of a mesh in SVG format

3D Scanning tools Alignment ICP based range map alignment tool, for putting meshes into the same reference space.
Merging of multiple meshes the Poisson surface reconstruction source code (kindly provided by by Michael Kazhdan and Matthew Bolitho) have been included in.

OpenGL Shader based rendering (write your own shader!) compatible with Typhoon Lab's Shader Designer
Large rendering (up to 16k x 16k) for high quality printing

The history of the all performed cleaning/editing actions can be re-played on different meshes or saved and for archival purposes.

Extendible plugins based architecture, writing new mesh processing functions, colorization filters and support for different file formats is quite easy! Look at PlugIn Samples


https://www.youtube.com/user/MrPMeshLabTutorials/videos - 50 tutorials
