---
title: get_FadeInDuration()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τη χρονική διάρκεια για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση float.
type: docs
weight: 326
url: /el/aspose.slides/audioframe/get_fadeinduration/
---
## AudioFrame::get_FadeInDuration() μέθοδος

Καθορίζει τη χρονική διάρκεια για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**.

```cpp
float Aspose::Slides::AudioFrame::get_FadeInDuration() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορίστε τη διάρκεια του αρχικού fade για 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)