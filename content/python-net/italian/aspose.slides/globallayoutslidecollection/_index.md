---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection classe

Rappresenta una raccolta di tutte le diapositive di layout nella presentazione.  
Estende la classe LayoutSlideCollection con metodi per aggiungere/duplicare le diapositive di layout nel contesto dell'unione delle collezioni individuali dei layout di master.

**Eredità:**[`GlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/it/aspose.slides/layoutslidecollection)

Il tipo GlobalLayoutSlideCollection espone i seguenti membri:

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## Metodi

| Nome | Descrizione |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/it/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | Aggiunge una copia di una diapositiva di layout specificata alla presentazione. |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/it/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | Aggiunge una copia di una diapositiva di layout specificata alla presentazione. |
| [`get_by_type(self, type)`](/slides/python-net/it/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | Restituisce la prima diapositiva di layout del tipo specificato.<br/>            Un tipo di diapositiva di layout da trovare.[`LayoutSlide`](/slides/python-net/it/aspose.slides/layoutslide) con il tipo specificato o None se non sono state trovate diapositive. |
| [`remove(self, value)`](/slides/python-net/it/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | Rimuove un layout dalla collezione. |
| [`remove_unused(self)`](/slides/python-net/it/aspose.slides/globallayoutslidecollection/remove_unused/#) | Rimuove le diapositive di layout non utilizzate (diapositive di layout il cui HasDependingSlides è false). |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/it/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | Aggiunge una nuova diapositiva di layout alla presentazione. |

### Vedi anche
* classe [`GlobalLayoutSlideCollection`](/slides/python-net/it/aspose.slides/globallayoutslidecollection)
* classe [`LayoutSlideCollection`](/slides/python-net/it/aspose.slides/layoutslidecollection)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)