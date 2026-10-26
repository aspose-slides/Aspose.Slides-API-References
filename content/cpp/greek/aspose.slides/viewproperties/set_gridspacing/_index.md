---
title: set_GridSpacing()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που αποτελεί τη βάση του εγγράφου παρουσίασης, σε σημεία. Γράψτε float.
type: docs
weight: 105
url: /el/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) μέθοδος

Ορίζει το διάστημα πλέγματος που πρέπει να χρησιμοποιείται για το πλέγμα που αποτελεί τη βάση του εγγράφου παρουσίασης, σε σημεία. Γράψτε **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Παρατηρήσεις

Η τιμή του διαστήματος πλέγματος πρέπει να είναι θετικός αριθμός. Το τυπικό εύρος τιμών είναι από 1 mm (2.8349607 σημεία) έως 2 ίντσες (144 σημεία).

Ο παρακάτω κώδικας δείγματος δείχνει πώς να αλλάξετε το διάστημα πλέγματος σε μια παρουσίαση PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [ViewProperties](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)