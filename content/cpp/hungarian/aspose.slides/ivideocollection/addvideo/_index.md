---
title: AddVideo()
second_title: Aspose.Slides C++ API referencia
description: Egy videófájl másolatát adja hozzá egy másik prezentációból.
type: docs
weight: 14
url: /hu/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metódus


Egy videófájl másolatát adja hozzá egy másik prezentációból.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Forrás videó. |

### Visszatérési érték

Hozzáadott videó.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metódus


Létrehoz és videót ad hozzá egy prezentációhoz streamből.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A videó fájl hozzáadásához használt stream. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | A streamre alkalmazandó viselkedés. |

### Visszatérési érték

Hozzáadott [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metódus


Létrehoz és videót ad hozzá egy prezentációhoz bájt tömbből.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
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
* Osztály [IVideoCollection](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)