---
title: get_GridSpacing()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει το διάστιχο του πλέγματος που θα πρέπει να χρησιμοποιηθεί για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε σημεία. Ανάγνωση float.
type: docs
weight: 92
url: /el/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() μέθοδος


Επιστρέφει το διάστιχο του πλέγματος που πρέπει να χρησιμοποιηθεί για το πλέγμα που υποστηρίζει το έγγραφο παρουσίασης, σε μονάδες σημείου. Ανάγνωση **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Παρατηρήσεις


Η τιμή του διαστήματος του πλέγματος πρέπει να είναι θετικός αριθμός. Το τυπικό εύρος τιμών είναι από 1 mm (2.8349607 σημεία) έως 2 ίντσες (144 σημεία).

Ο παρακάτω κώδικας δείγματος δείχνει πώς να αλλάξετε το διάστημα του πλέγματος σε μια παρουσίαση PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [ViewProperties](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)