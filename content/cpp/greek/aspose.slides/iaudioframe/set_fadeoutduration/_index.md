---
title: set_FadeOutDuration()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τη χρονική διάρκεια για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε float.
type: docs
weight: 365
url: /el/aspose.slides/iaudioframe/set_fadeoutduration/
---
## IAudioFrame::set_FadeOutDuration(float) μέθοδος

Καθορίζει τη χρονική διάρκεια για το τελικό fade-out του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeOutDuration(float value)=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the ending fade for 500ms
audioFrame->set_FadeOutDuration(500.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)