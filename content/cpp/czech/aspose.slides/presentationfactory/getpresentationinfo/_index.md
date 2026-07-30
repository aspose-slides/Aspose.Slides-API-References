---
title: GetPresentationInfo()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nový objekt PresentationInfo ze souboru a sváže prezentaci s ním.
type: docs
weight: 27
url: /cs/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) metoda


Vytvoří nový objekt [PresentationInfo](../../presentationinfo/) ze souboru a sváže prezentaci s ním.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) soubor. |

### Návratová hodnota

[Presentation](../../presentation/) informace vázané na prezentaci.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metoda


Vytvoří nový objekt [PresentationInfo](../../presentationinfo/) ze streamu a sváže prezentaci s ním. Získá informace o prezentaci ve specifikovaném streamu.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) proud. |

### Návratová hodnota

[Presentation](../../presentation/) informace vázané na prezentaci.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IPresentationInfo](../../ipresentationinfo/)
* Třída [String](../../../system/string/)
* Třída [PresentationFactory](../)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)