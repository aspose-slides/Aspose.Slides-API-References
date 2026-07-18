---
title: set_ReturnToParent()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. Γράψτε bool. Προεπιλεγμένη τιμή: false"
type: docs
weight: 40
url: /el/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) μέθοδος

Ορίζει τη συμπεριφορά πλοήγησης στη παρουσίαση. Γράψτε **bool**. Προεπιλεγμένη τιμή: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Παρατηρήσεις

Η τιμή true της ιδιότητας καθορίζει τη συμπεριφορά επιστροφής στον γονέα στη παρουσίαση.

Παράδειγμα:
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Δείτε επίσης

* Κλάση [ZoomObject](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)