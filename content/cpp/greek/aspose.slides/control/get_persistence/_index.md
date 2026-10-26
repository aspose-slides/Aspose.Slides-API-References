---
title: get_Persistence()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά τη μέθοδο που χρησιμοποιείται για την αποθήκευση των ιδιοτήτων του ελέγχου ActiveX. Μόνο για ανάγνωση PersistenceType.
type: docs
weight: 1
url: /el/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() μέθοδος

Προκύπτει η μέθοδος που χρησιμοποιείται για την αποθήκευση των ιδιοτήτων του ελέγχου ActiveX. Μόνο για ανάγνωση [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## Σχόλια

Το επόμενο παράδειγμα δείχνει τη χρήση της ιδιότητας Persistence για τον έλεγχο εάν οι ιδιότητες του αντικειμένου ActiveX μπορούν να αλλάξουν ως ιδιότητες ActiveX βασισμένες σε XML: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Χρησιμοποιήστε τη δική σας μέθοδο για τη διαχείριση των ιδιοτήτων ActiveX που αποθηκεύονται στο δυικό αρχείο
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Δείτε επίσης

* Enum [PersistenceType](../../persistencetype/)
* Κλάση [Control](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)