---
title: Add()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής.
type: docs
weight: 27
url: /el/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) μέθοδος

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Η ετικέτα των κλειστών υποτίτλων. |
| filePath | [System::String](../../../system/string/) | Η διαδρομή του αρχείου WebVTT. |

### Τιμή επιστροφής

Το προστιθέμενο [ICaptions](../../icaptions/) αντικείμενο.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) μέθοδος

Προσθέτει κλειστούς υπότιτλους WebVTT στο τέλος της συλλογής από μια ροή.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Η ετικέτα των κλειστών υποτίτλων. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Η ροή εισόδου που περιέχει δεδομένα σε μορφή WebVTT. |

### Τιμή επιστροφής

Το προστιθέμενο [ICaptions](../../icaptions/) αντικείμενο.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptions](../../icaptions/)
* Class [String](../../../system/string/)
* Class [ICaptionsCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)