---
title: GetPresentationInfo()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo oggetto PresentationInfo dal file e lo associa alla presentazione.
type: docs
weight: 27
url: /it/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) method

Crea un nuovo oggetto [PresentationInfo](../../presentationinfo/) dal file e lo associa alla presentazione.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | file [Presentation](../../presentation/). |

### Valore di ritorno

Informazioni [Presentation](../../presentation/) associate alla presentazione.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) method

Crea un nuovo oggetto [PresentationInfo](../../presentationinfo/) dallo stream e lo associa alla presentazione. Ottiene informazioni sulla presentazione nello stream specificato.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | stream [Presentation](../../presentation/). |

### Valore di ritorno

Informazioni [Presentation](../../presentation/) associate alla presentazione.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationInfo](../../ipresentationinfo/)
* Classe [String](../../../system/string/)
* Classe [PresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)