---
title: get_TileOffsetX()
second_title: Aspose.Slides για C++ API Reference
description: Επιστρέφει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε σημεία. Μια θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή τη μετακινεί προς τα αριστερά. Ανάγνωση float.
type: docs
weight: 274
url: /el/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() μέθοδος

Επιστρέφει την οριζόντια μετατόπιση της υφής από το αρχικό σημείο του σχήματος σε σημεία. Μια θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή τη μετακινεί προς τα αριστερά. Ανάγνωση **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη διαμόρφωση γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την οριζόντια μετατόπιση της υφής στα 20 σημεία
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Δείτε επίσης

* Κλάση [PictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)