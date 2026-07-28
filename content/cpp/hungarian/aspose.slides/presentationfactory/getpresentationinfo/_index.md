---
title: GetPresentationInfo()
second_title: Aspose.Slides C++ API referencia
description: Új PresentationInfo objektumot hoz létre a fájlból, és a prezentációt ehhez köti.
type: docs
weight: 27
url: /hu/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) metódus

Új [PresentationInfo](../../presentationinfo/) objektumot hoz létre a fájlból, és a prezentációt ehhez köti.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) fájl. |

### Visszatérési érték

[Presentation](../../presentation/) információ a prezentációhoz kötve.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metódus

Új [PresentationInfo](../../presentationinfo/) objektumot hoz létre az adatfolyamból, és a prezentációt ehhez köti. Információt kap a megadott adatfolyamban lévő prezentációról.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) adatfolyam. |

### Visszatérési érték

[Presentation](../../presentation/) információ a prezentációhoz kötve.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPresentationInfo](../../ipresentationinfo/)
* Osztály [String](../../../system/string/)
* Osztály [PresentationFactory](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)