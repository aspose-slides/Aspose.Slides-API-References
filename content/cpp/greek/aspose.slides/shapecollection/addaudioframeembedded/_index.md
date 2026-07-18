---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχήματος. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή Presentation::get_Audios."
type: docs
weight: 287
url: /el/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο ήχου με ενσωματωμένο αρχείο WAV και το προσθέτει στο τέλος της συλλογής σχήματος. Ο ενσωματωμένος ήχος προστίθεται στη συλλογή [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Μία ροή εισόδου που περιέχει δεδομένα ήχου WAV για ενσωμάτωση. |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IAudioFrame](../../iaudioframe/).

## Παρατηρήσεις

Τα παρακάτω παραδείγματα δείχνουν πώς να δημιουργήσετε το πλαίσιο [Audio](../../audio/). 
```cpp
// Δημιουργεί μια κλάση παρουσίασης που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>();

// Λαμβάνει την πρώτη διαφάνεια
auto slide = pres->get_Slides()->idx_get(0);
// Φορτώνει το αρχείο ήχου wav σε ροή
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Προσθέτει το Πλαίσιο Ήχου
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Ορίζει τη Λειτουργία Αναπαραγωγής και την Ένταση του Ήχου
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Γράφει το αρχείο PowerPoint στον δίσκο
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο ήχου και το προσθέτει στο τέλος της συλλογής σχήματος χρησιμοποιώντας ένα υπάρχον αντικείμενο ήχου από τη λίστα [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| height | **float** | Το ύψος του νέου πλαισίου ήχου, σε μονάδες σημείου. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Μία παρουσία [IAudio](../../iaudio/) από τη συλλογή [Presentation::get_Audios](../../presentation/get_audios/). |

### Τιμή Επιστροφής

Το νέο δημιουργημένο [IAudioFrame](../../iaudioframe/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAudioFrame](../../iaudioframe/)
* Κλάση [Stream](../../../system.io/stream/)
* Κλάση [ShapeCollection](../)
* Κλάση [IAudio](../../iaudio/)
* Χώρος Ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)