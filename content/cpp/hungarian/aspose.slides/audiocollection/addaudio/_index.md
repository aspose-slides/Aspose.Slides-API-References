---
title: AddAudio()
second_title: Aspose.Slides C++ API hivatkozás
description: Hozzáad egy hangfájl másolatát egy másik bemutatóból.
type: docs
weight: 53
url: /hu/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) metódus


Hozzáad egy másik bemutató audiofájljának másolatát.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Forrás audio. |

### Visszatérési érték

Hozzáadott hang.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) metódus


Létrehoz és hozzáad egy hangot a bemutatóhoz egy adatfolyamból.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, amelyből a hangot hozzáadja. |

### Visszatérési érték

Hozzáadott hang.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) metódus


Létrehoz és hozzáad egy hangot a bemutatóhoz egy adatfolyamból.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Az adatfolyam, amelyből a videó hangot hozzáadja. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Az adatfolyamra alkalmazandó viselkedés. |

### Visszatérési érték

Hozzáadott hang.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) metódus


Létrehoz és hozzáad egy hangot a bemutatóhoz egy bájt tömbből.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
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
* Osztály [AudioCollection](../)
* Osztály [Stream](../../../system.io/stream/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)