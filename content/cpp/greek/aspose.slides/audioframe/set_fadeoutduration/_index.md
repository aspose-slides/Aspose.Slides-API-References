---
title: set_FadeOutDuration()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει τη χρονική διάρκεια για την τελική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε float.
type: docs
weight: 365
url: /el/aspose.slides/audioframe/set_fadeoutduration/
---
## AudioFrame::set_FadeOutDuration(float) method


Καθορίζει τη χρονική διάρκεια για την τελική εξασθένιση του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε **float**.

```cpp
void Aspose::Slides::AudioFrame::set_FadeOutDuration(float value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορίστε τη διάρκεια της τελικής εξασθένισης για 500 ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)