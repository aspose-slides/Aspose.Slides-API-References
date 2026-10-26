---
title: get_TileOffsetX()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε μονάδες σημείου. Μία θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή τη μετακινεί προς τα αριστερά. Ανάγνωση float.
type: docs
weight: 274
url: /el/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() μέθοδος

Επιστρέφει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε σημεία. Μια θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή την μετακινεί προς τα αριστερά. Ανάγνωση **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
```

## Σχόλια

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

* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)