---
title: set_ShowBackground()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ορίζει την τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Γράψτε bool. Προεπιλεγμένη τιμή: true"
type: docs
weight: 66
url: /el/aspose.slides/zoomobject/set_showbackground/
---
## ZoomObject::set_ShowBackground(bool) μέθοδος

Ορίζει την τιμή που καθορίζει αν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Γράψτε **bool**. Προεπιλεγμένη τιμή: true

```cpp
void Aspose::Slides::ZoomObject::set_ShowBackground(bool value) override
```

## Παρατηρήσεις

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