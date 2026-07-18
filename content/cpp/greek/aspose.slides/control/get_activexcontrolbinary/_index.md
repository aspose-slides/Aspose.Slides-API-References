---
title: get_ActiveXControlBinary()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει την επιμονή ενός ActiveX control όταν η μέθοδος που χρησιμοποιείται για την αποθήκευση είναι είτε PersistStream, PersistStreamInit ή PersistStorage.
type: docs
weight: 118
url: /el/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() μέθοδος


Καθορίζει την επιμονή ενός ActiveX control όταν η μέθοδος που χρησιμοποιείται για την αποθήκευση είναι είτε PersistStream, PersistStreamInit ή PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## Παρατηρήσεις


Το επόμενο παράδειγμα δείχνει τη χρήση της ιδιότητας ActiveXControlBinary για την αλλαγή ιδιοτήτων του ActiveX:

```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // Χρησιμοποιήστε τη δική σας μέθοδο για τη διαχείριση των ιδιοτήτων ActiveX που αποθηκεύονται στο δυαδικό αρχείο της
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [Control](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)