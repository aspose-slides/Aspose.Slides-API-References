---
title: get_CaptionTracks()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα ICaptionsCollection που περιέχει όλες τις γραμμές υποτίτλων.
type: docs
weight: 456
url: /el/aspose.slides/iaudioframe/get_captiontracks/
---
## IAudioFrame::get_CaptionTracks() μέθοδος

Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../icaptionscollection/) που περιέχει όλες τις γραμμές υποτίτλων.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IAudioFrame::get_CaptionTracks()=0
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
        // Αποθηκεύει τα δυαδικά δεδομένα του κομματιού υποτίτλου σε αρχείο .vtt
        for (auto&& captionTrack : audioFrame->get_CaptionTracks())
        {
            System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
        }
    }
}
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ICaptionsCollection](../../icaptionscollection/)
* Κλάση [IAudioFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)