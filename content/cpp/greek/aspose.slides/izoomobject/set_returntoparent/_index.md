---
title: set_ReturnToParent()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Γράψτε bool. Προεπιλεγμένη τιμή: false"
type: docs
weight: 40
url: /el/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) μέθοδος

Ορίζει τη συμπεριφορά πλοήγησης στην παρουσίαση. Γράψτε **bool**. Προεπιλεγμένη τιμή: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Παρατηρήσεις

Η τιμή True της ιδιότητας καθορίζει την επιστροφή στην γονική συμπεριφορά πλοήγησης στην παρουσίαση. 

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