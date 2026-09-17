---
title: ITextFrame class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/itextframe/
---
## ITextFrame clase

Representa un TextFrame.

El tipo ITextFrame expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`paragraphs`](/slides/python-net/es/aspose.slides/itextframe/paragraphs/) | Devuelve la lista de todos los párrafos en un marco.<br/>            Solo lectura [`IParagraphCollection`](/slides/python-net/es/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/es/aspose.slides/itextframe/text/) | Obtiene o establece el texto sin formato para un TextFrame.<br/>            Lectura/escritura **str**. |
| [`text_frame_format`](/slides/python-net/es/aspose.slides/itextframe/text_frame_format/) | Devuelve el objeto de formato para este objeto TextFrame.<br/>            Solo lectura [`ITextFrameFormat`](/slides/python-net/es/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/itextframe/hyperlink_queries/) | Proporciona acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/es/aspose.slides/itextframe/parent_shape/) | Devuelve la forma padre o None si el objeto padre no implementa la interfaz IShape<br/>            Solo lectura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/es/aspose.slides/itextframe/parent_cell/) | Devuelve la celda padre o None si el objeto padre no implementa la interfaz ICell.<br/>            Solo lectura [`ICell`](/slides/python-net/es/aspose.slides/icell). |
| [`slide`](/slides/python-net/es/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/es/aspose.slides/itextframe/presentation/) |  |

## Métodos

| Método | Descripción |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/es/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/es/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/es/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/es/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/es/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Une secuencias con el mismo formato en todos los párrafos. |
| [`split_text_by_columns(self)`](/slides/python-net/es/aspose.slides/itextframe/split_text_by_columns/#) | Divide el contenido de texto del [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe) en una matriz de cadenas, <br/>            donde cada elemento corresponde a una columna de texto separada dentro del marco. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/es/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Reemplaza todas las apariciones del texto especificado con otro texto especificado. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/es/aspose.slides/itextframe/replace_regex/#str-str) | Reemplaza todas las coincidencias de la expresión regular con la cadena especificada. |

### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)