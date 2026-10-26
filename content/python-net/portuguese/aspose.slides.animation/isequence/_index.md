---
title: ISequence class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides.animation/isequence/
---
## classe ISequence

Representa sequência (coleção de efeitos).

O tipo ISequence expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`count`](/slides/python-net/pt/aspose.slides.animation/isequence/count/) | Retorna o número de efeitos em uma sequência.<br/>            Somente leitura **int**. |
| [`trigger_shape`](/slides/python-net/pt/aspose.slides.animation/isequence/trigger_shape/) | Retorna ou define o alvo de forma para a sequência INTERACTIVE.<br/>            Se a sequência não for interativa então retorna None.<br/>            Leitura/gravação [`IShape`](/slides/python-net/pt/aspose.slides/ishape). |

Retorna um efeito no índice especificado.

## Indexador

| Nome | Descrição |
| :- | :- |
| [`[index]`](/slides/python-net/pt/aspose.slides.animation/isequence/__getitem__/) | Index |

## Métodos

| Método | Descrição |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/isequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Adiciona um novo efeito ao final da sequência. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/isequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Adiciona um novo efeito de animação para parágrafo ao final da sequência. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Adiciona o novo efeito de animação de gráfico para categoria ou série ao final da sequência. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/pt/aspose.slides.animation/isequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Adiciona o novo efeito de animação de gráfico para elementos em categoria ou série ao final da sequência. |
| [`remove(self, item)`](/slides/python-net/pt/aspose.slides.animation/isequence/remove/#ieffect) | Remove o efeito especificado de uma coleção. |
| [`remove_at(self, index)`](/slides/python-net/pt/aspose.slides.animation/isequence/remove_at/#int) | Remove um efeito de uma coleção. |
| [`clear(self)`](/slides/python-net/pt/aspose.slides.animation/isequence/clear/#) | Remove todos os efeitos de uma coleção. |
| [`remove_by_shape(self, shape)`](/slides/python-net/pt/aspose.slides.animation/isequence/remove_by_shape/#ishape) | Remove o efeito da forma especificada. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/pt/aspose.slides.animation/isequence/get_effects_by_shape/#ishape) | Retorna um array de efeitos para a forma especificada. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/pt/aspose.slides.animation/isequence/get_effects_by_paragraph/#iparagraph) | Retorna um array de efeitos para o parágrafo especificado. |
| [`get_count(self, shape)`](/slides/python-net/pt/aspose.slides.animation/isequence/get_count/#ishape) | Retorna a contagem de efeitos para a forma especificada. |

### Veja Também
* módulo [`aspose.slides.animation`](/slides/python-net/pt/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)