---
title: get_VolumeValue()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει την ένταση ήχου σε ποσοστά. Ανάγνωση float.
type: docs
weight: 378
url: /el/aspose.slides/audioframe/get_volumevalue/
---
## AudioFrame::get_VolumeValue() μέθοδος

Επιστρέφει την ένταση ήχου σε ποσοστά. Ανάγνωση **float**.

```cpp
float Aspose::Slides::AudioFrame::get_VolumeValue() override
```

## Σχόλια

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορίστε τη διάρκεια της αρχικής εξασθένισης σε 200ms
audioFrame->set_VolumeValue(85.0f);

pres->Save(u"AudioFrameValue_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)