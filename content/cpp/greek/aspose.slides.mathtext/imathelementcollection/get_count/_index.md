---
title: get_Count()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση int32_t.
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() μέθοδος

Επιστρέφει τον αριθμό των στοιχείων που περιέχονται πραγματικά στη συλλογή. Μόνο για ανάγνωση **int32_t**.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## Σημειώσεις

Παράδειγμα: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## Δείτε επίσης

* Κλάση [IMathElementCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)