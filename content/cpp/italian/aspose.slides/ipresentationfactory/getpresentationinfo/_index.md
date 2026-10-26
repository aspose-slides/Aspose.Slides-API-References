---
title: GetPresentationInfo()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene informazioni sulla presentazione nel file specificato.
type: docs
weight: 14
url: /it/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) metodo

Ottiene informazioni sulla presentazione nel file specificato.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) file. |

### Valore di ritorno

[Presentation](../../presentation/) informazioni

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metodo

Ottiene informazioni sulla presentazione nello stream specificato.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) stream. |

### Valore di ritorno

[Presentation](../../presentation/) informazioni.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationInfo](../../ipresentationinfo/)
* Classe [String](../../../system/string/)
* Classe [IPresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)