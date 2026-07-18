---
title: set_TileOffsetX()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ορίζει την οριζόντια μετατόπιση της υφής από το σημείο προέλευσης του σχήματος σε μονάδες σημείου. Μια θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή τη μετακινεί προς τα αριστερά. Γράψτε float.
type: docs
weight: 287
url: /el/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) μέθοδος

Ορίζει την οριζόντια μετατόπιση της υφής από το σημείο προέλευσης του σχήματος σε μονάδες σημείου. Μια θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή τη μετακινεί προς τα αριστερά. Γράψτε **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Παρατηρήσεις


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την οριζόντια μετατόπιση της υφής σε 20 σημεία
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Δείτε επίσης

* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)