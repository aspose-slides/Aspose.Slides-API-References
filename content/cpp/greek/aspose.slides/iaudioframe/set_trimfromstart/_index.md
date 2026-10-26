---
title: set_TrimFromStart()
second_title: Αναφορά API του Aspose.Slides για C++ 
description: Καθορίζει τη διάρκεια χρόνου που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Γράψτε float.
type: docs
weight: 417
url: /el/aspose.slides/iaudioframe/set_trimfromstart/
---
## IAudioFrame::set_TrimFromStart(float) μέθοδος


Καθορίζει τη διάρκεια χρόνου που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromStart(float value)=0
```

## Παρατηρήσεις


Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορίστε το χρόνο περικοπής από την αρχή 1.5 δευτερόλεπτα
audioFrame->set_TrimFromStart(1500.0f);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)