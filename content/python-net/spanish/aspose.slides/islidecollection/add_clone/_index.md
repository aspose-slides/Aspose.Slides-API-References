---
title: add_clone method
second_title: Aspose.Slides para Python a través de .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Agrega una copia de una diapositiva especificada al final de la colección.

### Devuelve

Nueva diapositiva.



```python
def add_clone(self, source_slide):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |

### Observaciones

Al clonar una diapositiva entre presentaciones diferentes, el maestro de la diapositiva también puede clonarse.
            Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de 
            múltiples clones del mismo maestro de diapositiva.
            La clonación manual de maestros de diapositivas no será ni evitada ni registrada.
            Si necesita más control sobre el proceso de clonación, use
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** o
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** para clonar diapositivas,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** o
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** para clonar diseños y
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** para clonar maestros.



## add_clone(self, source_slide, section) {#islide-isection}
Agrega una copia de una diapositiva especificada al final de la sección especificada.

### Devuelve

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

### Devuelve

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
            El diseño apropiado se seleccionará automáticamente del maestro especificado 
            (el diseño apropiado es el diseño con el mismo Tipo o Nombre que 
            el diseño de la diapositiva fuente). Si no existe un diseño apropiado entonces
            el diseño de la diapositiva fuente será clonado (si allowCloneMissingLayout 
            es verdadero) o se lanzará PptxEditException (si allowCloneMissingLayout
            es falso).

### Devuelve

Nueva diapositiva.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/es/aspose.slides/islide) | Diapositiva a clonar. |
| dest_master | [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide) | Maestro de diapositiva para una nueva diapositiva. |
| allow_clone_missing_layout | **bool** | Si no hay un diseño apropiado en el maestro especificado, entonces el diseño de la <br/><br/>            diapositiva fuente será clonado (si allowCloneMissingLayout es verdadero) o <br/><br/>            se lanzará PptxEditException (si allowCloneMissingLayout es falso). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Lanzada si no hay un diseño apropiado en el maestro especificado y <br/>            allowCloneMissingLayout es falso. |



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide)
* clase [`ISection`](/slides/python-net/es/aspose.slides/isection)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* clase [`ISlideCollection`](/slides/python-net/es/aspose.slides/islidecollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)