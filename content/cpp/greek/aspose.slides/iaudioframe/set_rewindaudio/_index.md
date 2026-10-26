---
title: set_RewindAudio()
second_title: Aspose.Slides για την αναφορά API C++
description: Καθορίζει εάν ένας ήχος επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. Γράψτε bool.
type: docs
weight: 248
url: /el/aspose.slides/iaudioframe/set_rewindaudio/
---
## IAudioFrame::set_RewindAudio(bool) μέθοδος

Καθορίζει εάν ένα αρχείο ήχου επαναφέρεται αυτόματα στην αρχή μετά την αναπαραγωγή. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::IAudioFrame::set_RewindAudio(bool value)=0
```

## Σχόλια

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ορισμός ήχου για αναπαραγωγή σε όλες τις διαφάνειες
audioFrame->set_PlayAcrossSlides(true);

// Ορισμός ήχου για αυτόματη επαναφορά στην αρχή μετά την αναπαραγωγή
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)