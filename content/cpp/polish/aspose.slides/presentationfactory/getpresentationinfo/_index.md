---
title: GetPresentationInfo()
second_title: Odwołanie API Aspose.Slides dla C++
description: Tworzy nowy obiekt PresentationInfo z pliku i powiązuje z nim prezentację.
type: docs
weight: 27
url: /pl/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) metoda


Tworzy nowy [PresentationInfo](../../presentationinfo/) obiekt z pliku i powiązuje prezentację z nim.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) plik. |

### Wartość zwracana

[Presentation](../../presentation/) informacje powiązane z prezentacją.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metoda


Tworzy nowy [PresentationInfo](../../presentationinfo/) obiekt ze strumienia i powiązuje prezentację z nim. Pobiera informacje o prezentacji w określonym strumieniu.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) strumień. |

### Wartość zwracana

[Presentation](../../presentation/) informacje powiązane z prezentacją.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationInfo](../../ipresentationinfo/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)