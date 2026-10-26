---
title: set_GridSpacing()
second_title: Aspose.Slides – Αναφορά API για C++
description: Ορίζει την απόσταση του πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε μονάδες σημείου. Γράψτε float.
type: docs
weight: 105
url: /el/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) μέθοδος


Ορίζει την απόσταση του πλέγματος που θα πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε μονάδες σημείου. Γράψτε **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Παρατηρήσεις


Η τιμή της απόστασης του πλέγματος πρέπει να είναι θετικός αριθμός. Το τυπικό εύρος τιμών είναι από 1 mm (2.8349607 μονάδες σημείου) έως 2 ίντσες (144 μονάδες σημείου). 

Ο παρακάτω κώδικας δείγματος δείχνει πώς να αλλάξετε την απόσταση του πλέγματος σε μια παρουσίαση PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IViewProperties](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)