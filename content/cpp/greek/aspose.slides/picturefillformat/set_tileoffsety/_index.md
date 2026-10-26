---
title: set_TileOffsetY()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζει την κατακόρυφη μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες σημείου. Μια θετική τιμή μετακινεί την υφή προς τα κάτω, ενώ μια αρνητική τιμή τη μετακινεί προς τα πάνω. Γράψτε float.
type: docs
weight: 313
url: /el/aspose.slides/picturefillformat/set_tileoffsety/
---
## PictureFillFormat::set_TileOffsetY(float) μέθοδος


Ορίζει την κατακόρυφή μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες σημείου. Μία θετική τιμή μετακινεί την υφή προς τα κάτω, ενώ μια αρνητική τιμή τη μετακινεί προς τα πάνω. Γράψτε **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetY(float value) override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή πλήρωσης εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία πλήρωσης εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την κατακόρυφη μετατόπιση της υφής σε -50 σημεία
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Δείτε επίσης

* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)