---
title: Sequence class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.animation/sequence/
---
## Sequence classe

Rappresenta una sequenza (collezione di effetti).

Il tipo Sequence espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`count`](/slides/python-net/it/aspose.slides.animation/sequence/count/) | Restituisce il numero di effetti in una sequenza.<br/>            Solo lettura **int**. |
| [`trigger_shape`](/slides/python-net/it/aspose.slides.animation/sequence/trigger_shape/) | Restituisce o imposta il target della forma per la sequenza INTERACTIVE.<br/>            Se la sequenza non è interattiva, restituisce None.<br/>            Lettura/scrittura [`IShape`](/slides/python-net/it/aspose.slides/ishape). |

Restituisce un effetto all'indice specificato.

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides.animation/sequence/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_effect(self, shape, effect_type, subtype, trigger_type)`](/slides/python-net/it/aspose.slides.animation/sequence/add_effect/#ishape-effecttype-effectsubtype-effecttriggertype) | Aggiunge un nuovo effetto alla fine della sequenza. |
| [`add_effect(self, paragraph, effect_type, subtype, trigger_type)`](/slides/python-net/it/aspose.slides.animation/sequence/add_effect/#iparagraph-effecttype-effectsubtype-effecttriggertype) | Aggiunge un nuovo effetto di animazione per il paragrafo alla fine della sequenza. |
| [`add_effect(self, chart, type, index, effect_type, subtype, trigger_type)`](/slides/python-net/it/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartmajorgroupingtype-int-effecttype-effectsubtype-effecttriggertype) | Aggiunge il nuovo effetto di animazione del grafico per categoria o serie alla fine della sequenza. |
| [`add_effect(self, chart, type, series_index, categories_index, effect_type, subtype, trigger_type)`](/slides/python-net/it/aspose.slides.animation/sequence/add_effect/#asposeslideschartsichart-effectchartminorgroupingtype-int-int-effecttype-effectsubtype-effecttriggertype) | Aggiunge il nuovo effetto di animazione del grafico per gli elementi in categoria o serie alla fine della sequenza. |
| [`remove(self, item)`](/slides/python-net/it/aspose.slides.animation/sequence/remove/#ieffect) | Rimuove l'effetto specificato da una collezione. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides.animation/sequence/remove_at/#int) | Rimuove un effetto da una collezione. |
| [`clear(self)`](/slides/python-net/it/aspose.slides.animation/sequence/clear/#) | Rimuove tutti gli effetti da una collezione. |
| [`remove_by_shape(self, shape)`](/slides/python-net/it/aspose.slides.animation/sequence/remove_by_shape/#ishape) | Rimuove l'effetto per la forma specificata. |
| [`get_effects_by_shape(self, shape)`](/slides/python-net/it/aspose.slides.animation/sequence/get_effects_by_shape/#ishape) | Restituisce un array di effetti per la forma specificata. |
| [`get_effects_by_paragraph(self, paragraph)`](/slides/python-net/it/aspose.slides.animation/sequence/get_effects_by_paragraph/#iparagraph) | Restituisce un array di effetti per il paragrafo specificato. |
| [`get_count(self, shape)`](/slides/python-net/it/aspose.slides.animation/sequence/get_count/#ishape) | Restituisce il conteggio degli effetti per la forma specificata. |

### Vedi anche
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)