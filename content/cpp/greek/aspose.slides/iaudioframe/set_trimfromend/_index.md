---
title: set_TrimFromEnd()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει τη διάρκεια χρόνου που πρέπει να αφαιρεθεί από το τέλος του πολυμέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Γράψτε float.
type: docs
weight: 443
url: /el/aspose.slides/iaudioframe/set_trimfromend/
---
## IAudioFrame::set_TrimFromEnd(float) μέθοδος

Καθορίζει τη διάρκεια χρόνου που πρέπει να αφαιρεθεί από το τέλος του πολυμέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_TrimFromEnd(float value)=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the end trimming time 2 seconds
audioFrame->set_TrimFromEnd(2000.0f);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)