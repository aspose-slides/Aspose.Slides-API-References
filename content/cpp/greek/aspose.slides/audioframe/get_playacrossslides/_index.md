---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. Διαβάζει bool.
type: docs
weight: 209
url: /el/aspose.slides/audioframe/get_playacrossslides/
---
## AudioFrame::get_PlayAcrossSlides() μέθοδος

Καθορίζει εάν ο ήχος παίζει σε όλες τις διαφάνειες. Read **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_PlayAcrossSlides() override
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ορισμός ήχου να παίζει σε όλες τις διαφάνειες
audioFrame->set_PlayAcrossSlides(true);

// Ορισμός ήχου για αυτόματη επαναφορά στην αρχή μετά την αναπαραγωγή
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)