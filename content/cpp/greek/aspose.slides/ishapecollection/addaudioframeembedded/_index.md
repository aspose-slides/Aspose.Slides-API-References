---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios.
type: docs
weight: 248
url: /el/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχημάτων. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε μονάδες. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε μονάδες. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε μονάδες. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε μονάδες. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Μία ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

### Return Value

Το πρόσφατα δημιουργημένο [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχημάτων χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε μονάδες. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε μονάδες. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε μονάδες. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε μονάδες. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Μια παρουσία [IAudio](../../iaudio/) από τη συλλογή Presentation.Audios. |

### Return Value

Το πρόσφατα δημιουργημένο [IAudioFrame](../../iaudioframe/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudioFrame](../../iaudioframe/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [IShapeCollection](../)
* Κλάση [IAudio](../../iaudio/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)