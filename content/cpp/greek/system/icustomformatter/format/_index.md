---
title: Format()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει μια αναπαράσταση συμβολοσειράς μιας τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας το καθορισμένο μορφότυπο.
type: docs
weight: 1
url: /el/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method

Επιστρέφει μια αναπαράσταση συμβολοσειράς μιας τιμής που αντιπροσωπεύεται από το τρέχον αντικείμενο χρησιμοποιώντας το καθορισμένο μορφότυπο.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| format | [System::String](../../string/) | Η μορφή συμβολοσειράς |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Το αντικείμενο που θα μορφοποιηθεί |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Το αντικείμενο που παρέχει τις πληροφορίες μορφοποίησης |

### Τιμή Επιστροφής

Η αναπαράσταση συμβολοσειράς του **arg** μορφοποιημένης σύμφωνα με τη μορφή που καθορίζεται από **format** και **formatProvider**

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [String](../../string/)
* Κλάση [Object](../../object/)
* Κλάση [IFormatProvider](../../iformatprovider/)
* Κλάση [ICustomFormatter](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)