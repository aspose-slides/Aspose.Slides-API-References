---
title: set_VolumeValue()
second_title: Aspose.Slides για την Αναφορά API C++
description: Ορίζει την ένταση ήχου σε ποσοστά. Γράψτε float.
type: docs
weight: 391
url: /el/aspose.slides/audioframe/set_volumevalue/
---
## AudioFrame::set_VolumeValue(float) μέθοδος

Ορίζει την ένταση ήχου σε ποσοστά. Γράψτε **float**.

```cpp
void Aspose::Slides::AudioFrame::set_VolumeValue(float value) override
```

## Σχόλια

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορισμός της διάρκειας του αρχικού fade για 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)