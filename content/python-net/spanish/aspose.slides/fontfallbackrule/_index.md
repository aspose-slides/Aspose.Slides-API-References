---
title: FontFallBackRule class
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/fontfallbackrule/
---
## FontFallBackRule clase

Representa la regla de sustitución de fuentes

El tipo FontFallBackRule expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/es/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Crea una nueva instancia. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/es/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Crea una nueva instancia. |

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`range_start_index`](/slides/python-net/es/aspose.slides/fontfallbackrule/range_start_index/) | Obtiene el primer índice del rango Unicode continuo. |
| [`range_end_index`](/slides/python-net/es/aspose.slides/fontfallbackrule/range_end_index/) | Obtiene el último índice del rango Unicode continuo. |
| [`count`](/slides/python-net/es/aspose.slides/fontfallbackrule/count/) | Obtiene el número de fuentes realmente definidas para el rango.<br/>            Solo lectura **int**. |

Obtiene el nombre de la fuente en el índice especificado.
            Solo lectura [`IFontFallBackRule`](/slides/python-net/es/aspose.slides/ifontfallbackrule).

## Indexador

| Nombre | Descripción |
| :- | :- |
| [`[index]`](/slides/python-net/es/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/es/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Añade una(s) nueva(s) fuente(s) a la lista de fuentes de sustitución. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/es/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Añade nuevas fuentes a la lista de fuentes de sustitución. |
| [`to_array(self)`](/slides/python-net/es/aspose.slides/fontfallbackrule/to_array/#) | Crea y devuelve una matriz con todas las fuentes de sustitución para esta regla. |
| [`to_array(self, start_index, count)`](/slides/python-net/es/aspose.slides/fontfallbackrule/to_array/#int-int) | Crea y devuelve una matriz con todas las fuentes de sustitución del rango especificado en la lista. |
| [`clear(self)`](/slides/python-net/es/aspose.slides/fontfallbackrule/clear/#) | Elimina todas las fuentes de la lista. |
| [`remove(self, font_name)`](/slides/python-net/es/aspose.slides/fontfallbackrule/remove/#str) | Elimina la primera aparición de una fuente de sustitución específica de la lista. |
| [`remove_at(self, index)`](/slides/python-net/es/aspose.slides/fontfallbackrule/remove_at/#int) | Elimina la fuente de sustitución en el índice especificado de la lista. |
| [`index_of(self, font_name)`](/slides/python-net/es/aspose.slides/fontfallbackrule/index_of/#str) | Devuelve el índice de la regla especificada en la colección. |

### Ver también
* clase [`IFontFallBackRule`](/slides/python-net/es/aspose.slides/ifontfallbackrule)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)