---
title: set_RewindAudio()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: Καθορίζει αν ο ήχος επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. Γράψτε bool.
type: docs
weight: 248
url: /el/aspose.slides/audioframe/set_rewindaudio/
---
## AudioFrame::set_RewindAudio(bool) μέθοδος


Καθορίζει αν ο ήχος επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. Γράψτε **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_RewindAudio(bool value) override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Set Audio to play across the slides
audioFrame->set_PlayAcrossSlides(true);

// Set Audio to automatically rewind to start after playing
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)