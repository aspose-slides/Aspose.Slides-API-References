---
title: get_TrimFromStart()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Διαβάζεται float.
type: docs
weight: 404
url: /el/aspose.slides/iaudioframe/get_trimfromstart/
---
## IAudioFrame::get_TrimFromStart() μέθοδος

Καθορίζει τη διάρκεια χρόνου που θα αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Διαβάζεται **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_TrimFromStart()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορισμός χρόνου κοπής από την αρχή 1.5 δευτερόλεπτα
audioFrame->set_TrimFromStart(1500.0f);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)