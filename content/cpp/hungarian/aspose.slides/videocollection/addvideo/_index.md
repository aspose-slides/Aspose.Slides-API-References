---
title: AddVideo()
second_title: Aspose.Slides C++ API referencia
description: Egy másik prezentációból egy videofájl másolatát adja hozzá.
type: docs
weight: 53
url: /hu/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) method

Egy másik prezentációból egy videofájl másolatát adja hozzá.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Forrás videó. |

### Visszatérési érték

Hozzáadott videó.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) method

Létrehozza és hozzáad egy videót a prezentációhoz egy adatfolyamból.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Adatfolyam, amelyből a videófájlt hozzáadja. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | A viselkedés, amely az adatfolyamra lesz alkalmazva. |

### Visszatérési érték

Hozzáadott [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) method

Létrehozza és hozzáad egy videót a prezentációhoz egy bájttömbből.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bájt. |

### Visszatérési érték

Hozzáadott videó.

## Lásd még

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IVideo](../../ivideo/)
* Osztály [VideoCollection](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)