---
title: IHtmlGenerator class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.export/ihtmlgenerator/
---
## IHtmlGenerator classe

Gerador HTML.

O tipo IHtmlGenerator expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`slide_image_size`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/slide_image_size/) | Retorna o tamanho da imagem do slide.<br/>            Somente leitura **aspose.slides.SizeF**. |
| [`slide_image_size_unit`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/slide_image_size_unit/) | Retorna a unidade em que o tamanho da imagem do slide é especificado.<br/>            Somente leitura [`SvgCoordinateUnit`](/slides/python-net/pt/aspose.slides.export/svgcoordinateunit). |
| [`slide_image_size_unit_code`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/slide_image_size_unit_code/) | Retorna o código CSS da unidade em que o tamanho da imagem do slide é especificado.<br/>            Somente leitura **str**. |
| [`previous_slide_index`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/previous_slide_index/) | Retorna o índice do slide renderizado anteriormente ou -1 se o primeiro slide está sendo renderizado.<br/>            Somente leitura **int**. |
| [`slide_index`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/slide_index/) | Retorna o índice do slide que está sendo renderizado atualmente.<br/>            Somente leitura **int**. |
| [`next_slide_index`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/next_slide_index/) | Retorna o índice de um slide que será renderizado após o slide atual ou -1 se o último slide está sendo renderizado.<br/>            Somente leitura **int**. |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_html(self, html)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_html/#str) | Adiciona texto HTML formatado. |
| [`add_html(self, html)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_html/#listchar) | Adiciona texto HTML formatado. |
| [`add_html(self, html, start_index, length)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_html/#listchar-int-int) | Adiciona texto HTML formatado. |
| [`add_text(self, text)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_text/#str) | Adiciona texto simples aos arquivos html, substituindo caracteres especiais por entidades html.<br/>            Quebras de linha e espaços em branco não são substituídos. |
| [`add_text(self, text)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_text/#listchar) | Adiciona texto simples aos arquivos html, substituindo caracteres especiais por entidades html.<br/>            Quebras de linha e espaços em branco não são substituídos. |
| [`add_text(self, text, start_index, length)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_text/#listchar-int-int) | Adiciona texto simples aos arquivos html, substituindo caracteres especiais por entidades html.<br/>            Quebras de linha e espaços em branco não são substituídos. |
| [`add_attribute_value(self, value)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_attribute_value/#str) | Cita o valor do atributo e o adiciona ao arquivo html. |
| [`add_attribute_value(self, value)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar) | Cita o valor do atributo e o adiciona ao arquivo html. |
| [`add_attribute_value(self, value, start_index, length)`](/slides/python-net/pt/aspose.slides.export/ihtmlgenerator/add_attribute_value/#listchar-int-int) | Cita o valor do atributo e o adiciona ao arquivo html. |

### Veja Também
* módulo [`aspose.slides.export`](/slides/python-net/pt/aspose.slides.export)
* biblioteca [`Aspose.Slides`](/slides/python-net)