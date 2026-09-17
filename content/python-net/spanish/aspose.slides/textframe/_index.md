---
title: TextFrame class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/textframe/
---
## Clase TextFrame

Representa un TextFrame.

El tipo TextFrame expone los siguientes miembros:

## Propiedades

| Property | Description |
| :- | :- |
| [`paragraphs`](/slides/python-net/es/aspose.slides/textframe/paragraphs/) | Devuelve la lista de todos los párrafos en un marco.<br/>            Solo lectura [`IParagraphCollection`](/slides/python-net/es/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/es/aspose.slides/textframe/text/) | Obtiene o establece el texto plano de un TextFrame.<br/>            Lectura/escritura **str**. |
| [`text_frame_format`](/slides/python-net/es/aspose.slides/textframe/text_frame_format/) | Devuelve el objeto de formato para este objeto TextFrame.<br/>            Solo lectura [`ITextFrameFormat`](/slides/python-net/es/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/es/aspose.slides/textframe/hyperlink_queries/) | Proporciona acceso fácil a los hipervínculos contenidos.<br/>            Solo lectura [`IHyperlinkQueries`](/slides/python-net/es/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/es/aspose.slides/textframe/slide/) | Devuelve la diapositiva padre de un TextFrame.<br/>            Solo lectura [`IBaseSlide`](/slides/python-net/es/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/es/aspose.slides/textframe/presentation/) | Devuelve la presentación padre de un TextFrame.<br/>            Solo lectura [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/es/aspose.slides/textframe/parent_shape/) | Devuelve la forma padre o None si el objeto padre no implementa la interfaz IShape<br/>            Solo lectura [`IShape`](/slides/python-net/es/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/es/aspose.slides/textframe/parent_cell/) | Devuelve la celda padre o None si el objeto padre no implementa la interfaz ICell.<br/>            Solo lectura [`ICell`](/slides/python-net/es/aspose.slides/icell). |

## Métodos

| Method | Description |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/es/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/es/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/es/aspose.slides/textframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Resalta todas las coincidencias del texto de muestra con el color especificado. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/es/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/es/aspose.slides/textframe/highlight_regex/#str-asposepydrawingcolor) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/es/aspose.slides/textframe/join_portions_with_same_formatting/#) | Une secuencias con el mismo formato en todos los párrafos. |
| [`split_text_by_columns(self)`](/slides/python-net/es/aspose.slides/textframe/split_text_by_columns/#) | Divide el contenido de texto del [`ITextFrame`](/slides/python-net/es/aspose.slides/itextframe) en una matriz de cadenas,<br/>            donde cada elemento corresponde a una columna de texto separada dentro del marco. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/es/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Reemplaza todas las apariciones del texto especificado con otro texto especificado. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/es/aspose.slides/textframe/replace_regex/#str-str) | Reemplaza todas las coincidencias de la expresión regular con la cadena especificada. |


### Ver también
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)