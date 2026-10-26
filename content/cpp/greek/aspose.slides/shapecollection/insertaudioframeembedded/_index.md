---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation::get_Audios."
type: docs
weight: 300
url: /el/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης που ξεκινά από το μηδέν, όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο ήχου και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης που ξεκινά από το μηδέν, όπου θα εισαχθεί το πλαίσιο ήχου. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε σημεία. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Μια παρουσία [IAudio](../../iaudio/) από τη συλλογή [Presentation::get_Audios](../../presentation/get_audios/) για ενσωμάτωση. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IAudioFrame](../../iaudioframe/).

## Δείτε επίσης

* Τύπος-ορισμός [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudioFrame](../../iaudioframe/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [ShapeCollection](../)
* Κλάση [IAudio](../../iaudio/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)