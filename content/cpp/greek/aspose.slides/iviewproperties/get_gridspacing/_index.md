---
title: get_GridSpacing()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει την απόσταση του πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε points. Ανάγνωση float.
type: docs
weight: 92
url: /el/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() μέθοδος


Επιστρέφει την απόσταση του πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε points. Ανάγνωση **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Σχόλια


Η τιμή της απόστασης του πλέγματος πρέπει να είναι θετικός αριθμός. Το τυπικό εύρος τιμών είναι από 1 mm (2.8349607 points) έως 2 ίντσες (144 points). 

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