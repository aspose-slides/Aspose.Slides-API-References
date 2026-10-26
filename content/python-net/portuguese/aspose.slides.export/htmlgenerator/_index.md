---
title: HtmlGenerator class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.export/htmlgenerator/
---
## HtmlGenerator classe

Gerador HTML.

O tipo HtmlGenerator expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`slide_image_size`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/slide_image_size/) | Retorna o tamanho da imagem do slide.<br/>            Somente leitura [`SizeF`](/slides/python-net/pt/aspose.slides/sizef). |
| [`slide_image_size_unit`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/slide_image_size_unit/) | Retorna a unidade em que o tamanho da imagem do slide é especificado.<br/>            Somente leitura [`SvgCoordinateUnit`](/slides/python-net/pt/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/slide_image_size_unit_code/) | Retorna o código CSS da unidade na qual o tamanho da imagem do slide é especificado.<br/>            Somente leitura **str**. |
| [`previous_slide_index`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/previous_slide_index/) | Retorna o índice do slide previamente renderizado ou -1 se o primeiro slide está sendo renderizado.<br/>            Somente leitura **int**. |
| [`slide_index`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/slide_index/) | Retorna o índice do slide que está sendo renderizado no momento.<br/>            Somente leitura **int**. |
| [`next_slide_index`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/next_slide_index/) | Retorna o índice de um slide que será renderizado após o slide atual ou -1 se o slide atual for o último.<br/>            Somente leitura **int**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_html/#str) | Adiciona texto HTML formatado. |
| [`add_html(self, html)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_html/#listchar) | Adiciona texto HTML formatado. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_html/#listchar-int-int) | Adiciona texto HTML formatado. |
| [`add_text(self, text)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_text/#str) | Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML.<br/>            Quebras de linha e espaços em branco não são substituídos. |
| [`add_text(self, text)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_text/#listchar) | Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML.<br/>            Quebras de linha e espaços em branco não são substituídos. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_text/#listchar-int-int) | Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML.<br/>            Quebras de linha e espaços em branco não são substituídos. |
| [`add_attribute_value(self, value)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_attribute_value/#str) | Cita o valor do atributo e o adiciona ao arquivo HTML. |
| [`add_attribute_value(self, value)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar) | Cita o valor do atributo e o adiciona ao arquivo HTML. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/pt/aspose.slides.export/htmlgenerator/add_attribute_value/#listchar-int-int) | Cita o valor do atributo e o adiciona ao arquivo HTML. |

### Veja Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)