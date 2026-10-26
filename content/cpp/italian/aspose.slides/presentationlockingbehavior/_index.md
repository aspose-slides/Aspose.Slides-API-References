---
title: PresentationLockingBehavior
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta il comportamento relativo al trattamento della sorgente IPresentation (file o System::IO::Stream) durante il caricamento e l'utilizzo di un'istanza di IPresentation."
type: docs
weight: 6748
url: /it/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enum


Rappresenta il comportamento relativo al trattamento della [IPresentation](../ipresentation/) sorgente (file o [System::IO::Stream](../../system.io/stream/)) durante il caricamento e l'utilizzo di un'istanza di [IPresentation](../ipresentation/).

```cpp
enum class PresentationLockingBehavior
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| LoadAndRelease | 0 | La sorgente sarà bloccata solo per il tempo di esecuzione del costruttore [IPresentation](../ipresentation/). |
| KeepLocked | 1 | La sorgente sarà bloccata per l'intera durata dell'istanza [IPresentation](../ipresentation/), finché non verrà eliminata. |

## Osservazioni


La sorgente è il parametro passato al costruttore [IPresentation](../ipresentation/). Nell'esempio seguente, la sorgente è il file \"pres.pptx\": 


```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
}
```


In questo esempio, la sorgente (file \"pres.pptx\") sarà bloccata per la durata dell'istanza [IPresentation](../ipresentation/), ovvero non potrà essere modificata o eliminata da altri processi. 
## Vedi anche

* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)