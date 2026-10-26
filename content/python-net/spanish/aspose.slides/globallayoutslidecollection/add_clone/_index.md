---
title: add_clone method
second_title: Referencia de la API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Añade una copia de una diapositiva de diseño especificada a la presentación.

### Devuelve

Diapositiva añadida.



```python
def add_clone(self, source_layout):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diapositiva a clonar. |

### Observaciones

Al clonar un diseño entre presentaciones diferentes, el maestro del diseño también puede clonarse para mantener el formato original.  
Se utiliza un registro interno para rastrear maestros clonados automáticamente y evitar la creación de múltiples clones del mismo maestro.  
La clonación manual de maestros no será ni impedida ni registrada.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Añade una copia de una diapositiva de diseño especificada a la presentación.

### Devuelve

Diapositiva añadida.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diapositiva a clonar. |
| dest_master | [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide) | Diapositiva maestra para un nuevo diseño. |

### Observaciones

1) El nuevo diseño se enlazará con el maestro definido en la presentación de destino.  
   Por lo tanto, esto es análogo a copiar/pegar con la opción "Use Destination Theme" en PowerPoint.  
2) Un análogo de este método es el método **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** accedido mediante la propiedad [`IMasterSlide.layout_slides`](/slides/python-net/es/aspose.slides/imasterslide/layout_slides).



### Ver también
* clase [`GlobalLayoutSlideCollection`](/slides/python-net/es/aspose.slides/globallayoutslidecollection)
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)