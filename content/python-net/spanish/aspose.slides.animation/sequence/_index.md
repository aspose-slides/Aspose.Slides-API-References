---
title: Sequence class
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.animation/sequence/
---
## Clase Sequence

Representa una secuencia (colección de efectos).

El tipo Sequence expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`count`](/slides/python-net/es/aspose.slides.animation/sequence/count/) | Devuelve el número de efectos en una secuencia.<br/>            Solo lectura **int**. |
| [`trigger_shape`](/slides/python-net/es/aspose.slides.animation/sequence/trigger_shape/) | Devuelve o establece el objetivo de forma para la secuencia INTERACTIVE.<br/>            Si la secuencia no es interactiva entonces devuelve None.<br/>            Lectura/escritura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |

Devuelve un efecto en el índice especificado.

## Indexador

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides.animation/sequence/__getitem__/) |  |

## Métodos

| Method | Description |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/es/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Agregar nuevo efecto al final de la secuencia. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/es/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Agregar nuevo efecto de animación para párrafo al final de la secuencia. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/es/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Añade el nuevo efecto de animación de gráfico para categoría o serie al final de la secuencia. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/es/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Añade el nuevo efecto de animación de gráfico para elementos en categoría o serie al final de la secuencia. |
| [`remove(self, item)`](/slides/python-net/es/aspose.slides.animation/sequence/remove/#ieffect) | Elimina el efecto especificado de una colección. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides.animation/sequence/remove_at/#int) | Elimina un efecto de una colección. |
| [`clear(self)`](/slides/python-net/es/aspose.slides.animation/sequence/clear/#) | Elimina todos los efectos de una colección. |
| [`remove_by_shape(self, shape)`](/slides/python-net/es/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Elimina el efecto para la forma especificada. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/es/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Devuelve una matriz de efectos para la forma especificada. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/es/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Devuelve una matriz de efectos para el párrafo especificado. |
| [`get_count(self, shape)`](/slides/python-net/es/aspose.slides.animation/sequence/get_count/#ishape) | Devuelve el recuento de efectos para la forma especificada. |

### Ver también
* módulo [`aspose.slides.animation`](/slides/python-net/es/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)