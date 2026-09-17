---
title: insert_clone method
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

### Devuelve

Diapositiva insertada.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice de la nueva diapositiva. |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |

### Observaciones

Al clonar una diapositiva entre diferentes presentaciones, el maestro de la diapositiva también puede clonarse.
Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro de diapositiva.
La clonación manual de maestros de diapositivas no será ni evitada ni registrada.
Si necesita mayor control sobre el proceso de clonación, use
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** o
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** para clonar diapositivas y
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** para clonar maestros.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Inserta una copia de una diapositiva especificada en la posición especificada de la colección.

### Devuelve

Diapositiva insertada.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice de la nueva diapositiva. |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diapositiva de diseño para la nueva diapositiva. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Inserta una copia de una diapositiva fuente especificada en la posición especificada de la colección.
Se seleccionará automáticamente un diseño apropiado del maestro especificado (el diseño apropiado es el diseño con el mismo Tipo o Nombre que el diseño de la diapositiva fuente). Si no hay un diseño apropiado, el diseño de la diapositiva fuente se clonará (si allowCloneMissingLayout es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout es falso).

### Devuelve

Diapositiva insertada.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index | **int** | Índice de la nueva diapositiva. |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |
| dest_master | [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide) | Maestro de diapositiva para la nueva diapositiva. |
| allow_clone_missing_layout | **bool** | Si no hay un diseño apropiado en el maestro especificado, entonces el diseño de la <br/><br/>            diapositiva fuente se clonará (si allowCloneMissingLayout es verdadero) o <br/><br/>            se lanzará PptxEditException (si allowCloneMissingLayout es falso). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Se lanza si no hay un diseño apropiado en el maestro especificado y <br/>            allowCloneMissingLayout es falso. |



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* clase [`SlideCollection`](/slides/python-net/es/aspose.slides/slidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)