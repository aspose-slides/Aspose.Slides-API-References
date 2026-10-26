---
title: AddAudio()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα αντίγραφο αρχείου ήχου από μια άλλη παρουσίαση.
type: docs
weight: 14
url: /el/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) μέθοδος

Προσθέτει ένα αντίγραφο αρχείου ήχου από μια άλλη παρουσίαση.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Πηγή ήχου. |

### Τιμή επιστροφής

Προστέθηκε ήχος.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) μέθοδος

Δημιουργεί και προσθέτει ένα ήχο σε μια παρουσίαση από ροή.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία να προστεθεί ήχος. |

### Τιμή επιστροφής

Προστέθηκε ήχος.

Αποσυρμένο
:   Χρησιμοποιήστε AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Η μέθοδος θα αφαιρεθεί στην έκδοση 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) μέθοδος

Δημιουργεί και προσθέτει ένα ήχο σε μια παρουσίαση από ροή.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία να προστεθεί ήχος βίντεο. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

### Τιμή επιστροφής

Προστέθηκε ήχος.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) μέθοδος

Δημιουργεί και προσθέτει ένα ήχο σε μια παρουσίαση από πίνακα byte.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Τιμή επιστροφής

Προστέθηκε ήχος.

## Δείτε επίσης

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [IAudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)