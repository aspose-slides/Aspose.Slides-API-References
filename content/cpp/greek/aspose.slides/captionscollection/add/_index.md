---
title: Add()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής.
type: docs
weight: 27
url: /el/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) μέθοδος

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Η ετικέτα των κλειστών υπότιτλων. |
| filePath | [System::String](../../../system/string/) | Η διαδρομή προς το αρχείο WebVTT. |

### Τιμή Επιστροφής

Το προστεθέν [ICaptions](../../icaptions/) αντικείμενο.

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) μέθοδος

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής από ροή.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Η ετικέτα των κλειστών υπότιτλων. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Η είσοδος ροή που περιέχει δεδομένα σε μορφή WebVTT. |

### Τιμή Επιστροφής

Το προστεθέν [ICaptions](../../icaptions/) αντικείμενο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ICaptions](../../icaptions/)
* Κλάση [String](../../../system/string/)
* Κλάση [CaptionsCollection](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)