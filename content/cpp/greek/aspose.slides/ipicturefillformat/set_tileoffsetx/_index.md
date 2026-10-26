---
title: set_TileOffsetX()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ορίζει την οριζόντια απόκλιση της υφής από την προέλευση του σχήματος σε σημεία. Μια θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή τη μετακινεί προς τα αριστερά. Γράψτε float.
type: docs
weight: 287
url: /el/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) μέθοδος


Ορίζει την οριζόντια απόκλιση της υφής από την προέλευση του σχήματος σε σημεία. Μία θετική τιμή μετακινεί την υφή προς τα δεξιά, ενώ μια αρνητική τιμή τη μετακινεί προς τα αριστερά. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Παρατηρήσεις



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Λαμβάνει τη μορφή γεμίσματος εικόνας του σχήματος
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Ορίζει τη λειτουργία γεμίσματος εικόνας σε Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Ορίζει την οριζόντια απόκλιση της υφής σε 20 σημεία
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Δείτε επίσης

* Κλάση [IPictureFillFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)