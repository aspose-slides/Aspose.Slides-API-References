---
title: get_RewindAudio()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει αν ο ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. Διαβάζει bool.
type: docs
weight: 235
url: /el/aspose.slides/audioframe/get_rewindaudio/
---
## AudioFrame::get_RewindAudio() μέθοδος


Καθορίζει αν ο ήχος επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή. Διαβάζει **bool**.

```cpp
bool Aspose::Slides::AudioFrame::get_RewindAudio() override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameLinked(50.0f, 50.0f, 100.0f, 100.0f, u"sampleaudio.wav");

// Ορισμός ήχου ώστε να παίζει σε όλες τις διαφάνειες
audioFrame->set_PlayAcrossSlides(true);

// Ορισμός ήχου ώστε να επανέρχεται αυτόματα στην αρχή μετά την αναπαραγωγή
audioFrame->set_RewindAudio(true);

pres->Save(u"AudioFrame_out.pptx", Aspose::Slides::Export::SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)