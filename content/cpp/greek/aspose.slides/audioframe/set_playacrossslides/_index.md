---
title: set_PlayAcrossSlides()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. Γράψτε bool.
type: docs
weight: 222
url: /el/aspose.slides/audioframe/set_playacrossslides/
---
## AudioFrame::set_PlayAcrossSlides(bool) μέθοδος


Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. Γράψτε **bool**.

```cpp
void Aspose::Slides::AudioFrame::set_PlayAcrossSlides(bool value) override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ορίστε τον ήχο να παίζει σε όλες τις διαφάνειες
audioFrame->set_PlayAcrossSlides(true);

// Ρυθμίστε τον ήχο ώστε να επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)