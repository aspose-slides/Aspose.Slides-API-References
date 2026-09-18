---
title: Sequence class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.animation/sequence/
---
## Sequence classe

Representa Sequence (coleção de efeitos).

O tipo Sequence expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`count`](/slides/python-net/pt/aspose.slides.animation/sequence/count/) | Retorna o número de efeitos em uma sequense.<br/>            Somente leitura **int**. |
| [`trigger_shape`](/slides/python-net/pt/aspose.slides.animation/sequence/trigger_shape/) | Retorna ou define o alvo da forma para a sequência INTERACTIVE.<br/>            Se a sequência não for interativa então retorna None.<br/>            Leitura/gravação [`IShape`](/slides/python-net/pt/aspose.slides/ishape). |

Retorna um efeito no índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.animation/sequence/__getitem__/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Adiciona um novo efeito ao final da sequência. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Adiciona um novo efeito de animação para parágrafo ao final da sequência. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Adiciona o novo efeito de animação de gráfico para elementos em categoria ou série ao final da sequência. |
| [`remove(self, item)`](/slides/python-net/pt/aspose.slides.animation/sequence/remove/#ieffect) | Remove o efeito especificado de uma coleção. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides.animation/sequence/remove_at/#int) | Remove um efeito de uma coleção. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides.animation/sequence/clear/#) | Remove todos os efeitos de uma coleção. |
| [`remove_by_shape(self, shape)`](/slides/python-net/pt/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Remove o efeito para a forma especificada. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/pt/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Retorna a matriz de efeitos para a forma especificada. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/pt/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Retorna a matriz de efeitos para o parágrafo especificado. |
| [`get_count(self, shape)`](/slides/python-net/pt/aspose.slides.animation/sequence/get_count/#ishape) | Retorna a contagem de efeitos para a forma especificada. |

### Veja Também
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)