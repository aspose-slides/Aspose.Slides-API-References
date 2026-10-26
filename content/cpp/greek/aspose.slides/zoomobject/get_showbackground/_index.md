---
title: get_ShowBackground()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Λαμβάνει τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Διαβάζει bool. Προεπιλεγμένη τιμή: true"
type: docs
weight: 53
url: /el/aspose.slides/zoomobject/get_showbackground/
---
## ZoomObject::get_ShowBackground() μέθοδος

Λαμβάνει την τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Διαβάζει **bool**. Προεπιλεγμένη τιμή: true

```cpp
bool Aspose::Slides::ZoomObject::get_ShowBackground() override
```

## Σχόλια

Το παράδειγμα δείχνει την αφαίρεση του φόντου μιας εικόνας ενός αντικειμένου Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Δείτε επίσης

* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)