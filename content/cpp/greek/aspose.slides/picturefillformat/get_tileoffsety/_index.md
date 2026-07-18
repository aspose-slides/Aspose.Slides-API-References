---
title: get_TileOffsetY()
second_title: Aspose.Slides για την Αναφορά API C++
description: Επιστρέφει την κάθετη μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες σημείου. Μια θετική τιμή μετακινεί την υφή προς τα κάτω, ενώ μια αρνητική τιμή τη μετακινεί προς τα πάνω. Διαβάστε float.
type: docs
weight: 300
url: /el/aspose.slides/picturefillformat/get_tileoffsety/
---
## PictureFillFormat::get_TileOffsetY() μέθοδος

Επιστρέφει την κάθετη μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες σημείου. Μια θετική τιμή μετακινεί την υφή προς τα κάτω, ενώ μια αρνητική τιμή τη μετακινεί προς τα πάνω. Διαβάστε **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetY() override
```

## Σημειώσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την κάθετη μετατόπιση της υφής σε -50 μονάδες σημείου
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Δείτε επίσης

* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)