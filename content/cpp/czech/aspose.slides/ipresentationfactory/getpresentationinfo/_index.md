---
title: GetPresentationInfo()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Získá informace o prezentaci v určeném souboru.
type: docs
weight: 14
url: /cs/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) metoda

Získá informace o prezentaci v zadaném souboru.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) soubor. |

### Návratová hodnota

[Presentation](../../presentation/) informace

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metoda

Získá informace o prezentaci ve specifikovaném proudu.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) proud. |

### Návratová hodnota

[Presentation](../../presentation/) informace.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IPresentationInfo](../../ipresentationinfo/)
* třída [String](../../../system/string/)
* třída [IPresentationFactory](../)
* třída [Stream](../../../system.io/stream/)
* jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)