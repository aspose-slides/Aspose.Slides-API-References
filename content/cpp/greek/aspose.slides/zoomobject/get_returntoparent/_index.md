---
title: get_ReturnToParent()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Ανακτά τη συμπεριφορά πλοήγησης στη παρουσίαση διαφανειών. Ανάγνωση bool. Προεπιλεγμένη τιμή: false"
type: docs
weight: 27
url: /el/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() μέθοδος


Λαμβάνει τη συμπεριφορά πλοήγησης στη παρουσίαση διαφανειών. Ανάγνωση **bool**. Προεπιλεγμένη τιμή: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Παρατηρήσεις


Η αληθής τιμή της ιδιότητας καθορίζει τη συμπεριφορά επιστροφής στον γονέα στη παρουσίαση διαφανειών. 

Παράδειγμα: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Δείτε επίσης

* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)