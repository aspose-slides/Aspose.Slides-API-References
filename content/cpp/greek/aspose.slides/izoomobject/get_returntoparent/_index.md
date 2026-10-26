---
title: get_ReturnToParent()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ανακτά τη συμπεριφορά πλοήγησης στη παρουσίαση. Ανάγνωση bool. Προεπιλεγμένη τιμή: false"
type: docs
weight: 27
url: /el/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() μέθοδος

Ανακτά τη συμπεριφορά πλοήγησης στη διαφάνεια. Ανάγνωση **bool**. Προεπιλεγμένη τιμή: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Σχόλια

Η τιμή true της ιδιότητας καθορίζει τη συμπεριφορά επιστροφής στο γονικό αντικείμενο στη διαφάνεια. 

Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Δείτε επίσης

* Κλάση [IZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)