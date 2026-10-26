---
title: set_ShowBackground()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Γράψτε bool. Προεπιλεγμένη τιμή: true"
type: docs
weight: 66
url: /el/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) μέθοδος


Ορίζει τιμή που καθορίζει εάν το Zoom θα χρησιμοποιήσει το φόντο της διαφάνειας προορισμού. Γράψτε **bool**. Προεπιλεγμένη τιμή: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
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

* Κλάση [IZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)