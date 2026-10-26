---
title: get_TrimFromStart()
second_title: Aspose.Slides για C++ API Reference
description: Καθορίζει τη διάρκεια χρόνου που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση float.
type: docs
weight: 404
url: /el/aspose.slides/audioframe/get_trimfromstart/
---
## AudioFrame::get_TrimFromStart() method


Καθορίζει τη διάρκεια χρόνου που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromStart() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορισμός του χρόνου έναρξης κοπής 1.5 δευτερόλεπτα
audioFrame->set_TrimFromStart(1500.0f);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)