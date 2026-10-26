---
title: AddVideo()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσθέτει ένα αντίγραφο αρχείου βίντεο από μια άλλη παρουσίαση.
type: docs
weight: 14
url: /el/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) μέθοδος


Προσθέτει ένα αντίτυπο αρχείου βίντεο από άλλη παρουσίαση.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Πηγή βίντεο. |

### Τιμή επιστροφής

Προστέθηκε βίντεο.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) μέθοδος


Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από ροή.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία θα προστεθεί το αρχείο βίντεο. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

### Τιμή επιστροφής

Προστέθηκε [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) μέθοδος


Δημιουργεί και προσθέτει ένα βίντεο σε παρουσίαση από πίνακα byte.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Τιμή επιστροφής

Προστέθηκε βίντεο.

## Δείτε επίσης

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IVideo](../../ivideo/)
* Κλάση [IVideoCollection](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)