---
title: EnumValuesBase
second_title: Aspose.Slides για C++ Αναφορά API
description: Μια βασική κλάση για μια κλάση που αντιπροσωπεύει μεταπληροφορίες τύπου απαρίθμησης.
type: docs
weight: 807
url: /el/system/enumvaluesbase/
---
## EnumValuesBase κλάση


Μια βασική κλάση για μια κλάση που αντιπροσωπεύει μετα-πληροφορίες τύπου απαρίθμησης.

```cpp
class EnumValuesBase
```

## Μέθοδοι

| Μεθοδος | Περιγραφή |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Επιστρέφει έναν πίνακα με τα ονόματα των σταθερών σε μια καθορισμένη απαρίθμηση. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Επιστρέφει τον υποκείμενο τύπο της καθορισμένης απαρίθμησης. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Επιστρέφει έναν πίνακα που περιέχει όλες τις τιμές του καθορισμένου τύπου απαρίθμησης. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Επιστρέφει ένα αντικείμενο που αντιπροσωπεύει μια τιμή της σταθεράς απαρίθμησης του καθορισμένου τύπου απαρίθμησης με το καθορισμένο όνομα. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Μετατρέπει την καθορισμένη τιμή 64-bit ακέραιου χωρίς πρόσημο σε μέλος απαρίθμησης. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Μετατρέπει το καθορισμένο αντικείμενο με ακέραια τιμή σε μέλος απαρίθμησης. |
## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)