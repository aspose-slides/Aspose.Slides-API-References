---
title: set_FadeInDuration()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει τη χρονική διάρκεια για την αρχική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε float.
type: docs
weight: 339
url: /el/aspose.slides/audioframe/set_fadeinduration/
---
## AudioFrame::set_FadeInDuration(float) μέθοδος

Καθορίζει τη χρονική διάρκεια για την αρχική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeInDuration(float value) override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορίστε τη διάρκεια της αρχικής εξασθένισης σε 200 ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)