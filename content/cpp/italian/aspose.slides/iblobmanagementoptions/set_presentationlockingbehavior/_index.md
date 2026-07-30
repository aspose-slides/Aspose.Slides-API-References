---
title: set_PresentationLockingBehavior()
second_title: Riferimento API di Aspose.Slides per C++
description: "Questa proprietà definisce se un'istanza della classe Presentation può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di Presentation. Questo è un esempio:"
type: docs
weight: 14
url: /it/aspose.slides/iblobmanagementoptions/set_presentationlockingbehavior/
---
## IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior) metodo

Questa proprietà definisce se un'istanza della classe [Presentation](../../presentation/) può essere proprietaria della sorgente - file o stream durante la durata dell'istanza. Se l'istanza è proprietaria, blocca la sorgente. Questo aiuta a migliorare il consumo di memoria e le prestazioni durante il lavoro con i BLOB, ma la sorgente (stream o file) non può essere modificata durante la durata dell'istanza di [Presentation](../../presentation/). Questo è un esempio:

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_PresentationLockingBehavior(Aspose::Slides::PresentationLockingBehavior value)=0
```

## Osservazioni

```cpp
auto loadOptions = MakeObject<LoadOptions>();
loadOptions->get_BlobManagementOptions()->set_PresentationLockingBehavior(PresentationLockingBehavior::KeepLocked);
{
    auto pres = MakeObject<Presentation>(u"pres.pptx", loadOptions);
    // Verrà lanciata un'IOException perché pres.pptx è bloccato per tutta la durata di una Presentation
    // File::Delete(u"pres.pptx");
}
// after Presentation object destroyed, file is unlocked and can be deleted
IO::File::Delete(u"pres.pptx");
```

## Vedi anche

* Enum [PresentationLockingBehavior](../../presentationlockingbehavior/)
* Classe [IBlobManagementOptions](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)