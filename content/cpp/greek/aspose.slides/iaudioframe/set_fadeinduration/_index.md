---
title: set_FadeInDuration()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει τη χρονική διάρκεια για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε float.
type: docs
weight: 339
url: /el/aspose.slides/iaudioframe/set_fadeinduration/
---
## IAudioFrame::set_FadeInDuration(float) μέθοδος

Καθορίζει τη χρονική διάρκεια για το αρχικό fade-in του μέσου σε χιλιοστά του δευτερολέπτου. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_FadeInDuration(float value)=0
```

## Σημειώσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the duration of the starting fade for 200ms
audioFrame->set_FadeInDuration(200.0f);

pres->Save(u"AudioFrameFade_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)