---
title: MasterLayoutSlideCollection class
second_title: Referencia de API de Aspose.Slides para Python via .NET
description: 
type: docs
url: /es/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection clase

Representa una colección de todas las diapositivas de diseño de la diapositiva maestra definida.  
Extiende la clase LayoutSlideCollection con métodos para agregar/insertar/eliminar/clonar/reordenar diapositivas de diseño en el contexto de las colecciones individuales de diapositivas de diseño del maestro.

**Herencia:**[`MasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/es/aspose.slides/layoutslidecollection)

El tipo MasterLayoutSlideCollection expone los siguientes miembros:

## Indexer

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Devuelve la primera diapositiva de diseño del tipo especificado.<br/>            Un tipo de diapositiva de diseño a buscar.[`LayoutSlide`](/slides/python-net/es/aspose.slides/layoutslide) con el tipo especificado o None si no se encuentran diseños. |
| [`remove(self, value)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Elimina un diseño de la colección. |
| [`remove_unused(self)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Elimina diapositivas de diseño no usadas (diapositivas de diseño cuya propiedad HasDependingSlides es false). |
| [`add_clone(self, source_layout)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Añade una copia de una diapositiva de diseño especificada al final de la colección. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Inserta una copia de una diapositiva de diseño especificada en la posición indicada de la colección. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Añade una nueva diapositiva de diseño al final de la colección. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Inserta una nueva diapositiva de diseño en la posición indicada de la colección. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Elimina el elemento en el índice especificado de la colección. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Mueve la diapositiva de diseño de la colección a la posición indicada. |


### Ver también
* clase [`LayoutSlideCollection`](/slides/python-net/es/aspose.slides/layoutslidecollection)
* clase [`MasterLayoutSlideCollection`](/slides/python-net/es/aspose.slides/masterlayoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)