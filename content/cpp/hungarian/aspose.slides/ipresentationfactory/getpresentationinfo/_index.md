---
title: GetPresentationInfo()
second_title: Aspose.Slides for C++ API referencia
description: Információkat kér a megadott fájlban lévő prezentációról.
type: docs
weight: 14
url: /hu/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) metódus

Információkat kér a megadott fájlban lévő prezentációról.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) fájl. |

### Visszatérési érték

[Presentation](../../presentation/) információ

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) metódus

Információkat kér a megadott adatfolyamban lévő prezentációról.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) adatfolyam. |

### Visszatérési érték

[Presentation](../../presentation/) információ.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPresentationInfo](../../ipresentationinfo/)
* Osztály [String](../../../system/string/)
* Osztály [IPresentationFactory](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)