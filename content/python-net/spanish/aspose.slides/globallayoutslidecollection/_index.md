---
title: GlobalLayoutSlideCollection class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection clase

Representa una colección de todas las diapositivas de diseño en la presentación.  
Amplía la clase LayoutSlideCollection con métodos para agregar/clonar diapositivas de diseño en el contexto de la unión de las colecciones individuales de diapositivas de diseño maestras.

**Herencia:**[`GlobalLayoutSlideCollection`](/slides/python-net/es/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/es/aspose.slides/layoutslidecollection)

El tipo GlobalLayoutSlideCollection expone los siguientes miembros:

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/es/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Agrega una copia de una diapositiva de diseño especificada a la presentación. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/es/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Agrega una copia de una diapositiva de diseño especificada a la presentación. |
| [`get_by_type(self, type)`](/slides/python-net/es/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Devuelve la primera diapositiva de diseño del tipo especificado.<br/>            Un tipo de diapositiva de diseño a buscar.[`LayoutSlide`](/slides/python-net/es/aspose.slides/layoutslide) con el tipo especificado o None si no se encuentran diseños. |
| [`remove(self, value)`](/slides/python-net/es/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Elimina un diseño de la colección. |
| [`remove_unused(self)`](/slides/python-net/es/aspose.slides/globallayoutslidecollection/remove_unused/#) | Elimina las diapositivas de diseño no utilizadas (diapositivas de diseño cuya propiedad HasDependingSlides es false). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/es/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Agrega una nueva diapositiva de diseño a la presentación. |

### Ver también
* clase [`GlobalLayoutSlideCollection`](/slides/python-net/es/aspose.slides/globallayoutslidecollection)
* clase [`LayoutSlideCollection`](/slides/python-net/es/aspose.slides/layoutslidecollection)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)