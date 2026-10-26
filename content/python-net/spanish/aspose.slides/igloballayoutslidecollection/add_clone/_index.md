---
title: add_clone method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Agrega una copia de una diapositiva de diseño especificada a la presentación.

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

Al clonar un diseño entre distintas presentaciones, el maestro del diseño también puede clonarse
            para conservar el formato de origen.
            Se utiliza un registro interno para rastrear maestros clonados automáticamente y evitar la creación de 
            múltiples clones del mismo maestro.
            La clonación manual de maestros no será ni impedida ni registrada.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Agrega una copia de una diapositiva de diseño especificada a la presentación.

### Devuelve

Diapositiva añadida.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide) | Diapositiva a clonar. |
| dest_master | [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide) | Maestro de diapositiva para un nuevo diseño. |

### Observaciones

El nuevo diseño se enlazará con el maestro definido en la presentación de destino.
            Por lo tanto, es análogo a copiar/pegar con la opción "Usar tema de destino" en PowerPoint.



### Ver también
* clase [`IGlobalLayoutSlideCollection`](/slides/python-net/es/aspose.slides/igloballayoutslidecollection)
* clase [`ILayoutSlide`](/slides/python-net/es/aspose.slides/ilayoutslide)
* clase [`IMasterSlide`](/slides/python-net/es/aspose.slides/imasterslide)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)