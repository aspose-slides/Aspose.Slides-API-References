---
title: get_FadeInDuration()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τη χρονική διάρκεια για την αρχική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Διαβάζεται float.
type: docs
weight: 326
url: /el/aspose.slides/iaudioframe/get_fadeinduration/
---
## IAudioFrame::get_FadeInDuration() μέθοδος

Καθορίζει τη χρονική διάρκεια για την αρχική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Διαβάζεται **float**.

```cpp
virtual float Aspose::Slides::IAudioFrame::get_FadeInDuration()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορίστε τη διάρκεια της αρχικής εξασθένισης για 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)