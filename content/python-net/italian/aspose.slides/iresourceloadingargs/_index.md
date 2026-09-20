---
title: IResourceLoadingArgs class
second_title: Aspose.Slides per Python tramite .NET API Reference
description: 
type: docs
url: /it/aspose.slides/iresourceloadingargs/
---
## IResourceLoadingArgs classe

Interfaccia per gli argomenti di caricamento di risorse esterne.

Il tipo IResourceLoadingArgs espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`original_uri`](/slides/python-net/it/aspose.slides/iresourceloadingargs/original_uri/) | URI originale della risorsa come specificato nella presentazione importata. |
| [`uri`](/slides/python-net/it/aspose.slides/iresourceloadingargs/uri/) | URI della risorsa utilizzata per il download se **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            restituisce [`ResourceLoadingAction.DEFAULT`](/slides/python-net/it/aspose.slides/resourceloadingaction/DEFAULT). <br/>            Inizialmente è impostato sul URI originale della risorsa, ma può essere ridefinito a qualsiasi valore. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`set_data(self, data)`](/slides/python-net/it/aspose.slides/iresourceloadingargs/set_data/#bytes) | Imposta i dati forniti dall'utente della risorsa che vengono usati se **Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide** <br/>            restituisce [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/it/aspose.slides/resourceloadingaction/USER_PROVIDED). |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)