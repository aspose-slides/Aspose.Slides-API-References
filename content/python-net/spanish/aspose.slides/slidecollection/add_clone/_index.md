---
title: add_clone method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Agrega una copia de una diapositiva especificada al final de la colección.

### Valor devuelto

Nueva diapositiva.



```python
def add_clone(self, source_slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |

### Observaciones

Al clonar una diapositiva entre diferentes presentaciones, el master de la diapositiva también puede clonarse.
Se utiliza un registro interno para rastrear los masters clonados automáticamente y evitar la creación de
clones múltiples del mismo master de diapositiva.
La clonación manual de masters de diapositivas no será ni impedida ni registrada.
Si necesita más control sobre el proceso de clonación, utilice
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** o
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** para clonar diapositivas,
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** o
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** para clonar diseños y
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** para clonar masters.


## add_clone(self, source_slide, section) {#islide-isection}
Agrega una copia de una diapositiva especificada al final de la sección especificada.

### Valor devuelto

Nueva diapositiva.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |
| section | [`ISection`](/slides/python-net/es/aspose.slides/isection) | Sección para una nueva diapositiva. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Agrega una copia de una diapositiva especificada al final de la colección.

### Valor devuelto

Nueva diapositiva.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diseño de diapositiva para una nueva diapositiva. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Agrega una copia de una diapositiva fuente especificada al final de la colección.
Se seleccionará automáticamente un diseño apropiado del master especificado
(diseño apropiado es el diseño con el mismo Type o Name que el
diseño de la diapositiva fuente). Si no existe un diseño apropiado,
el diseño de la diapositiva fuente se clonará (si allowCloneMissingLayout
es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout
es falso).

### Valor devuelto

Nueva diapositiva.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |
| dest_master | [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide) | Master slide para una nueva diapositiva. |
| allow_clone_missing_layout | **bool** | Si no hay un diseño apropiado en el master especificado, entonces el diseño de la <br/><br/>            diapositiva fuente se clonará (si allowCloneMissingLayout es verdadero) o <br/><br/>            se lanzará PptxEditException (si allowCloneMissingLayout es falso). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Lanzada si no hay un diseño apropiado en el master especificado y <br/>            allowCloneMissingLayout es falso. |



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide)
* clase [`ISection`](/slides/python-net/es/aspose.slides/isection)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* clase [`SlideCollection`](/slides/python-net/es/aspose.slides/slidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)