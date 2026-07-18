---
title: get_FadeOutDuration()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τη διάρκεια χρόνου για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση float.
type: docs
weight: 352
url: /el/aspose.slides/audioframe/get_fadeoutduration/
---
## AudioFrame::get_FadeOutDuration() μέθοδος

Καθορίζει τη διάρκεια χρόνου για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeOutDuration() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορισμός διάρκειας του τελικού fade-out για 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)