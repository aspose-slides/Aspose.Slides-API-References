---
title: get_CaptionTracks()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αποκτά τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το audio frame. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα ICaptionsCollection που περιέχει όλα τα caption tracks.
type: docs
weight: 456
url: /el/aspose.slides/audioframe/get_captiontracks/
---
## AudioFrame::get_CaptionTracks() μέθοδος

Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το audio frame. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../icaptionscollection/) που περιέχει όλα τα caption tracks.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::AudioFrame::get_CaptionTracks() override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"audio with captions.pptx");
for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    if (System::ObjectExt::Is<IAudioFrame>(shape))
    {
        System::SharedPtr<IAudioFrame> audioFrame = System::ExplicitCast<IAudioFrame>(shape);
        // Αποθηκεύστε τα δυαδικά δεδομένα του κομματιού υπότιτλου ως αρχείο .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ICaptionsCollection](../../icaptionscollection/)
* Κλάση [AudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)