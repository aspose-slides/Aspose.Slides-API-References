---
title: AddAudio()
second_title: Aspose.Slides C++ API referencia
description: Hozzáad egy másik prezentációból származó hangfájl másolatát.
type: docs
weight: 14
url: /hu/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metódus


Hozzáad egy másik prezentációból származó hangfájl másolatát.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Forrás hang. |

### Visszatérési érték

Hozzáadott hang.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metódus


Létrehoz és hozzáad egy hangot egy prezentációhoz egy adatfolyamból.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Az audio hozzáadásához használt adatfolyam. |

### Visszatérési érték

Hozzáadott hang.

Elavult
:   Használja az AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior) metódust. A metódus a 17.10-es verzióban el lesz távolítva.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metódus


Létrehoz és hozzáad egy hangot egy prezentációhoz egy adatfolyamból.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A videó hangot hozzáadáshoz használt adatfolyam. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Az adatfolyamra alkalmazandó viselkedés. |

### Visszatérési érték

Hozzáadott hang.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metódus


Létrehoz és hozzáad egy hangot egy prezentációhoz egy bájttömbből.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bájt. |

### Visszatérési érték

Hozzáadott hang.

## Lásd még

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [IAudio](../../iaudio/)
* Osztály [IAudioCollection](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)