---
title: ITextFrame class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/itextframe/
---
## classe ITextFrame

Representa um TextFrame.

O tipo ITextFrame expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`paragraphs`](/slides/python-net/pt/aspose.slides/itextframe/paragraphs/) | Retorna a lista de todos os parágrafos em um quadro.<br/>            Somente leitura [`IParagraphCollection`](/slides/python-net/pt/aspose.slides/iparagraphcollection). |
| [`text`](/slides/python-net/pt/aspose.slides/itextframe/text/) | Obtém ou define o texto simples para um TextFrame.<br/>            Leitura/gravação **str**. |
| [`text_frame_format`](/slides/python-net/pt/aspose.slides/itextframe/text_frame_format/) | Retorna o objeto de formatação para este objeto TextFrame.<br/>            Somente leitura [`ITextFrameFormat`](/slides/python-net/pt/aspose.slides/itextframeformat). |
| [`hyperlink_queries`](/slides/python-net/pt/aspose.slides/itextframe/hyperlink_queries/) | Fornece acesso fácil a hyperlinks contidos.<br/>            Somente leitura [`IHyperlinkQueries`](/slides/python-net/pt/aspose.slides/ihyperlinkqueries). |
| [`parent_shape`](/slides/python-net/pt/aspose.slides/itextframe/parent_shape/) | Retorna a forma pai ou None se o objeto pai não implementar a interface IShape<br/>            Somente leitura [`IShape`](/slides/python-net/pt/aspose.slides/ishape). |
| [`parent_cell`](/slides/python-net/pt/aspose.slides/itextframe/parent_cell/) | Retorna a célula pai ou None se o objeto pai não implementar a interface ICell.<br/>            Somente leitura [`ICell`](/slides/python-net/pt/aspose.slides/icell). |
| [`slide`](/slides/python-net/pt/aspose.slides/itextframe/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/itextframe/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/pt/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor) | Realça todas as ocorrências do texto de amostra com a cor especificada. |
| [`highlight_text(self, text, highlight_color, options)`](/slides/python-net/pt/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itexthighlightingoptions) | Realça todas as ocorrências do texto de amostra com a cor especificada. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/pt/aspose.slides/itextframe/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Realça todas as ocorrências do texto de amostra com a cor especificada. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/pt/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor) | Realça todas as ocorrências da expressão regular com a cor especificada. |
| [`highlight_regex(self, regex, highlight_color, options)`](/slides/python-net/pt/aspose.slides/itextframe/highlight_regex/#str-asposepydrawingcolor-itexthighlightingoptions) | Realça todas as ocorrências da expressão regular com a cor especificada. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pt/aspose.slides/itextframe/join_portions_with_same_formatting/#) | Une execuções com a mesma formatação em todos os parágrafos. |
| [`split_text_by_columns(self)`](/slides/python-net/pt/aspose.slides/itextframe/split_text_by_columns/#) | Divide o conteúdo de texto do [`ITextFrame`](/slides/python-net/pt/aspose.slides/itextframe) em um array de strings,  <br/>            onde cada elemento corresponde a uma coluna de texto separada dentro do quadro. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/pt/aspose.slides/itextframe/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Substitui todas as ocorrências do texto especificado por outro texto especificado. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/pt/aspose.slides/itextframe/replace_regex/#str-str) | Substitui todas as correspondências da expressão regular pela string especificada. |


### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)