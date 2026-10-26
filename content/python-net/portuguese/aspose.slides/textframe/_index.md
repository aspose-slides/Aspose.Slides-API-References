---
title: TextFrame class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/textframe/
---
## TextFrame classe

Represents a TextFrame.

The TextFrame type exposes the following members:

## Properties

| Propriedade | Descrição |
| :- | :- |
| [`paragraphs`](/slides/python-net/pt/aspose.slides/textframe/paragraphs/) | Retorna a lista de todos os parágrafos em um quadro.<br/>            Somente leitura [`IParagraphCollection`](/slides/python-net/pt/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/pt/aspose.slides/textframe/text/) | Obtém ou define o texto simples para um TextFrame.<br/>            Leitura/Gravação **str**. |
| [`text_frame_format`](/slides/python-net/pt/aspose.slides/textframe/text_frame_format/) | Retorna o objeto de formatação para este objeto TextFrame.<br/>            Somente leitura [`ITextFrameFormat`](/slides/python-net/pt/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/textframe/hyperlink_queries/) | Fornece acesso fácil a hyperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`slide`](/slides/python-net/pt/aspose.slides/textframe/slide/) | Retorna o slide pai de um TextFrame.<br/>            Somente leitura [`IBaseSlide`](/slides/python-net/pt/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/pt/aspose.slides/textframe/presentation/) | Retorna a apresentação pai de um TextFrame.<br/>            Somente leitura [`IPresentation`](/slides/python-net/pt/aspose.slides/ipresentation). |
| [`parent_shape`](/slides/python-net/pt/aspose.slides/textframe/parent_shape/) | Retorna a forma pai ou None se o objeto pai não implementar a interface IShape<br/>            Somente leitura [`IShape`](/slides/python-net/pt/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/pt/aspose.slides/textframe/parent_cell/) | Retorna a célula pai ou None se o objeto pai não implementar a interface ICell.<br/>            Somente leitura [`ICell`](/slides/python-net/pt/aspose.slides/icell). |

## Methods

| Método | Descrição |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/pt/aspose.slides/textframe/highlight_text/#str-asposeslidescolor) | Destaca todas as correspondências do texto de exemplo com a cor especificada. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/pt/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itexthighlightingoptions) | Destaca todas as correspondências do texto de exemplo com a cor especificada. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/pt/aspose.slides/textframe/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Destaca todas as correspondências do texto de exemplo com a cor especificada. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/pt/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor-itexthighlightingoptions) | Destaca todas as correspondências da expressão regular com a cor especificada. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/pt/aspose.slides/textframe/highlight_regex/#str-asposeslidescolor) | Destaca todas as correspondências da expressão regular com a cor especificada. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/textframe/join_portions_with_same_formatting/#) | Une execuções com a mesma formatação em todos os parágrafos. |
| [`split_text_by_columns(self)`](/slides/python-net/pt/aspose.slides/textframe/split_text_by_columns/#) | Divide o conteúdo de texto do [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe) em um array de strings,  <br/>            onde cada elemento corresponde a uma coluna de texto separada dentro do quadro. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/pt/aspose.slides/textframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/pt/aspose.slides/textframe/replace_regex/#str-str) | Substitui todas as correspondências da expressão regular por uma string especificada. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)