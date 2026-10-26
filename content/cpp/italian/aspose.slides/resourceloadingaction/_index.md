---
title: ResourceLoadingAction
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la modalità di caricamento delle risorse esterne.
type: docs
weight: 6761
url: /it/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction enum


Specifica la modalità di caricamento delle risorse esterne.

```cpp
enum class ResourceLoadingAction
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) caricherà la risorsa esterna come di consueto. |
| Skip | 1 | [Aspose.Slides](../) salterà il caricamento della risorsa esterna. Verrà memorizzato solo un collegamento senza dati per un'immagine. |
| UserProvided | 2 | [Aspose.Slides](../) utilizzerà l'array di byte fornito dall'utente in [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) come dati dell'immagine. |

## Vedi anche

* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)