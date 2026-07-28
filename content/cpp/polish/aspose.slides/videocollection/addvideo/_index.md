---
title: AddVideo()
second_title: Aspose.Slides dla C++ - Referencja API
description: Dodaje kopię pliku wideo z innej prezentacji.
type: docs
weight: 53
url: /pl/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) metoda

Dodaje kopię pliku wideo z innej prezentacji.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Wideo źródłowe. |

### Wartość zwracana

Dodane wideo.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metoda

Tworzy i dodaje wideo do prezentacji ze strumienia.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, z którego dodać plik wideo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Zachowanie, które zostanie zastosowane do strumienia. |

### Wartość zwracana

Dodane [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) metoda

Tworzy i dodaje wideo do prezentacji z tablicy bajtów.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bajtów. |

### Wartość zwracana

Dodane wideo.

## Zobacz także

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [IVideo](../../ivideo/)
* Klasa [VideoCollection](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)