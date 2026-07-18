---
title: get_PlayAcrossSlides()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Καθορίζει εάν ένας ήχος παίζει σε όλες τις διαφάνειες. Ανάγνωση bool.
type: docs
weight: 209
url: /el/aspose.slides/iaudioframe/get_playacrossslides/
---
## IAudioFrame::get_PlayAcrossSlides() method

Καθορίζει εάν ένας ήχος παίζει σε όλες τις διαφάνειες. Ανάγνωση **bool**.

```cpp
virtual bool Aspose::Slides::IAudioFrame::get_PlayAcrossSlides()=0
```

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ορισμός ήχου να παίζει σε όλες τις διαφάνειες
audioFrame->set_PlayAcrossSlides(true);

// Ορισμός ήχου να επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)