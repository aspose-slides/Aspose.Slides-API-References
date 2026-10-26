---
title: insert_clone method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/islidecollection/insert_clone/
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

Al clonar una diapositiva entre presentaciones diferentes, el maestro de la diapositiva también puede ser clonado.  
Se utiliza un registro interno para rastrear los maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro de diapositiva.  
La clonación manual de maestros de diapositiva no será ni evitada ni registrada.  
Si necesita más control sobre el proceso de clonación, utilice  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** o  
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** para clonar diapositivas y  
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
Inserta una copia de una diapositiva origen especificada en la posición especificada de la colección.  
La disposición apropiada se seleccionará automáticamente del  
maestro especificado (la disposición apropiada es la que tiene el mismo Tipo o Nombre que  
la disposición de la diapositiva origen). Si no hay una disposición apropiada,  
la disposición de la diapositiva origen será clonada (si allowCloneMissingLayout  
es true) o se lanzará PptxEditException (si  
allowCloneMissingLayout es false).

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
| allow_clone_missing_layout | **bool** | Si no hay una disposición apropiada en el maestro especificado, entonces la disposición de la <br/><br/>            diapositiva origen será clonada (si allowCloneMissingLayout es true) o <br/><br/>            se lanzará PptxEditException (si allowCloneMissingLayout es false). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception) | Lanzada si no hay una disposición apropiada en el maestro especificado y allowCloneMissingLayout es false. |



### Ver también
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide)
* clase [`ISlide`](/slides/python-net/es/aspose.slides/islide)
* clase [`ISlideCollection`](/slides/python-net/es/aspose.slides/islidecollection)
* clase [`PptxEditException`](/slides/python-net/es/aspose.slides/pptxeditexception)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)