---
title: MasterLayoutSlideCollection class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection classe

Rappresenta una collezione di tutte le diapositive di layout della diapositiva master definita.  
Estende la classe LayoutSlideCollection con metodi per aggiungere/inserire/rimuovere/clonare/riorganizzare le diapositive di layout nel contesto delle singole collezioni di diapositive di layout del master.

**Inheritance:**[`MasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/it/aspose.slides/layoutslidecollection)

Il tipo MasterLayoutSlideCollection espone i seguenti membri:

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | Restituisce la prima diapositiva di layout del tipo specificato.<br/>            Un tipo di diapositiva di layout da trovare.[`LayoutSlide`](/slides/python-net/it/aspose.slides/layoutslide) con tipo specificato o None se non sono state trovate diapositive di layout. |
| [`remove(self, value)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | Rimuove un layout dalla collezione. |
| [`remove_unused(self)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/remove_unused/#) | Rimuove le diapositive di layout inutilizzate (diapositive di layout il cui HasDependingSlides è false). |
| [`add_clone(self, source_layout)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | Aggiunge una copia di una diapositiva di layout specificata alla fine della collezione. |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | Inserisce una copia di una diapositiva di layout specificata nella posizione specificata della collezione. |
| [`add(self, layout_type, layout_name)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | Aggiunge una nuova diapositiva di layout alla fine della collezione. |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | Inserisce una nuova diapositiva di layout nella posizione specificata della collezione. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/remove_at/#int) | Rimuove l'elemento all'indice specificato della collezione. |
| [`reorder(self, index, layout_slide)`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | Sposta la diapositiva di layout dalla collezione alla posizione specificata. |


### Vedi anche
* classe [`LayoutSlideCollection`](/slides/python-net/it/aspose.slides/layoutslidecollection)
* classe [`MasterLayoutSlideCollection`](/slides/python-net/it/aspose.slides/masterlayoutslidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)