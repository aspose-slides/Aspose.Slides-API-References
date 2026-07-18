---
title: get_TrimFromEnd()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τη διάρκεια του χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά τη διάρκεια της αναπαραγωγής, σε χιλιοστά του δευτερολέπτου. Ανάγνωση float.
type: docs
weight: 430
url: /el/aspose.slides/audioframe/get_trimfromend/
---
## AudioFrame::get_TrimFromEnd() μέθοδος


Καθορίζει τη διάρκεια του χρόνου που θα αφαιρεθεί από το τέλος του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Ανάγνωση **float**.

```cpp
float Aspose::Slides::AudioFrame::get_TrimFromEnd() override
```

## Σημειώσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Ορισμός χρόνου αποκοπής από το τέλος στα 2 δευτερόλεπτα
audioFrame->set_TrimFromEnd(2000.0f);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)