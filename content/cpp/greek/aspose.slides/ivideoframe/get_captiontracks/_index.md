---
title: get_CaptionTracks()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα ICaptionsCollection που περιέχει όλα τα κομμάτια υποτίτλων.
type: docs
weight: 261
url: /el/aspose.slides/ivideoframe/get_captiontracks/
---
## IVideoFrame::get_CaptionTracks() μέθοδος

Ανακτά τη συλλογή των κλειστών υπότιτλων που σχετίζονται με το πλαίσιο ήχου. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../icaptionscollection/) που περιέχει όλα τα κομμάτια υποτίτλων.

```cpp
virtual System::SharedPtr<ICaptionsCollection> Aspose::Slides::IVideoFrame::get_CaptionTracks()=0
```

## Σχόλια

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"video with captions.pptx");

for (auto&& shape : pres->get_Slide(0)->get_Shapes())
{
    System::SharedPtr<IVideoFrame> videoFrame = System::AsCast<IVideoFrame>(shape);
    if (videoFrame != nullptr)
    {
        continue;
    }

    for (auto&& captionTrack : videoFrame->get_CaptionTracks())
    {
        // Εξάγει τα δυαδικά δεδομένα των υποτίτλων και τα αποθηκεύει στο αρχείο
        System::IO::File::WriteAllBytes(System::Convert::ToString(captionTrack->get_CaptionId()) + u".vtt", captionTrack->get_BinaryData());
    }
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ICaptionsCollection](../../icaptionscollection/)
* Κλάση [IVideoFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)