---
title: set_TrimFromStart()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Γράψτε float.
type: docs
weight: 417
url: /el/aspose.slides/audioframe/set_trimfromstart/
---
## AudioFrame::set_TrimFromStart(float) μέθοδος

Καθορίζει τη χρονική διάρκεια που πρέπει να αφαιρεθεί από την αρχή του μέσου κατά την αναπαραγωγή, σε χιλιοστά του δευτερολέπτου. Γράψτε **float**.

```cpp
void Aspose::Slides::AudioFrame::set_TrimFromStart(float value) override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Προσθήκη πλαισίου ήχου
System::SharedPtr<IAudio> audio = pres->get_Audios()->AddAudio(System::IO::File::ReadAllBytes(u"sampleaudio.mp3"));
System::SharedPtr<IAudioFrame> audioFrame = pres->get_Slide(0)->get_Shapes()->AddAudioFrameEmbedded(50.0f, 50.0f, 100.0f, 100.0f, audio);

// Set the start trimming time 1.5 seconds
audioFrame->set_TrimFromStart(1500.0f);
```

## Δείτε επίσης

* Κλάση [AudioFrame](../)
* Χώρος ονόματος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)