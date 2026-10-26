---
title: AddVideo()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Dodaje kopię pliku wideo z innej prezentacji.
type: docs
weight: 14
url: /pl/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metoda

Dodaje kopię pliku wideo z innej prezentacji.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Źródłowe wideo. |

### Wartość zwracana

Dodano wideo.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda

Tworzy i dodaje wideo do prezentacji ze strumienia.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać plik wideo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Zachowanie, które zostanie zastosowane do strumienia. |

### Wartość zwracana

Dodano [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metoda

Tworzy i dodaje wideo do prezentacji z tablicy bajtów.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bajtów. |

### Wartość zwracana

Dodano wideo.

## Zobacz też

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [IVideo](../../ivideo/)
* Klasa [IVideoCollection](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)