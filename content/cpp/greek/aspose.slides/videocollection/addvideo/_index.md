---
title: AddVideo()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει ένα αντίγραφο ενός αρχείου βίντεο από μια άλλη παρουσίαση.
type: docs
weight: 53
url: /el/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) μέθοδος

Προσθέτει ένα αντίγραφο ενός αρχείου βίντεο από μια άλλη παρουσίαση.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Πηγή βίντεο. |

### Τιμή επιστροφής

Προστέθηκε βίντεο.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) μέθοδος

Δημιουργεί και προσθέτει ένα βίντεο σε μια παρουσίαση από ροή.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή από την οποία θα προστεθεί το αρχείο βίντεο. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Η συμπεριφορά που θα εφαρμοστεί στη ροή. |

### Τιμή επιστροφής

Προστέθηκε [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) μέθοδος

Δημιουργεί και προσθέτει ένα βίντεο σε μια παρουσίαση από πίνακα bytes.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Τιμή επιστροφής

Προστέθηκε βίντεο.

## Δείτε επίσης

* Απαρίθμηση [LoadingStreamBehavior](../../loadingstreambehavior/)
* Τύπος [SharedPtr](../../../system/sharedptr/)
* Τύπος [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IVideo](../../ivideo/)
* Κλάση [VideoCollection](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)