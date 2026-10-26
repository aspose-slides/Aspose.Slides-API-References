---
title: get_CaptionTracks()
second_title: Aspose.Slides για Αναφορά API C++
description: Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο βίντεο. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα ICaptionsCollection που περιέχει όλα τα κομμάτια υποτίτλων.
type: docs
weight: 261
url: /el/aspose.slides/videoframe/get_captiontracks/
---
## VideoFrame::get_CaptionTracks() μέθοδος


Λαμβάνει τη συλλογή των κλειστών υποτίτλων που σχετίζονται με το πλαίσιο βίντεο. Αυτή η ιδιότητα είναι μόνο για ανάγνωση και επιστρέφει ένα [ICaptionsCollection](../../icaptionscollection/) που περιέχει όλα τα κομμάτια υποτίτλων.

```cpp
System::SharedPtr<ICaptionsCollection> Aspose::Slides::VideoFrame::get_CaptionTracks() override
```

## Παρατηρήσεις


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
* Κλάση [VideoFrame](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)