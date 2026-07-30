---
title: get_PresentationLockingBehavior()
second_title: Riferimento API di Aspose.Slides per C++
description: "Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di Presentation. Questo è un esempio:"
type: docs
weight: 1
url: /it/aspose.slides/iblobmanagementoptions/get_presentationlockingbehavior/
---
## IBlobManagementOptions::get_PresentationLockingBehavior() metodo

Questa proprietà definisce se un'istanza della classe [Presentation](../../presentation/) può essere proprietaria della sorgente – file o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di [Presentation](../../presentation/). Questo è un esempio:

```cpp
virtual Aspose::Slides::PresentationLockingBehavior Aspose::Slides::IBlobManagementOptions::get_PresentationLockingBehavior()=0
```

## Osservazioni

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Verrà generata un'IOException perché pres.pptx è bloccato per l'intera durata della Presentation
    // File::Delete(u"pres.pptx");
}
// dopo che l'oggetto Presentation è stato distrutto, il file è sbloccato e può essere eliminato
IO::File::Delete(u"pres.pptx");
```

## Vedi anche

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Classe [IBlobManagementOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)