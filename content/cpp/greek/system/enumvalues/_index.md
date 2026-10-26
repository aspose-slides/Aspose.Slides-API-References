---
title: EnumValues
second_title: Αναφορά API Aspose.Slides για C++
description: Παρέχει μεταπληροφορίες σχετικά με τις σταθερές της απαρίθμησης του τύπου enum E.
type: docs
weight: 794
url: /el/system/enumvalues/
---
## EnumValues κλάση

Παρέχει μεταπληροφορίες σχετικά με τις σταθερές της απαρίθμησης του τύπου enum **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| E | Ο τύπος της απαρίθμησης |
## Μεθόδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Δημιουργεί ένα αντικείμενο. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Επιστρέφει έναν πίνακα που περιέχει όλα τα ονόματα της απαρίθμησης **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Ανακτά έναν πίνακα με τα ονόματα των σταθερών σε μια συγκεκριμένη απαρίθμηση. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Επιστρέφει τον υποκείμενο τύπο της συγκεκριμένης απαρίθμησης. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Επιστρέφει τον υποκείμενο τύπο της συγκεκριμένης απαρίθμησης. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Επιστρέφει τη συσκευασμένη τιμή της σταθεράς της απαρίθμησης με το συγκεκριμένο όνομα. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Επιστρέφει τη συσκευασμένη τιμή της σταθεράς της απαρίθμησης με τη συγκεκριμένη τιμή. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Επιστρέφει έναν πίνακα που περιέχει όλες τις τιμές της απαρίθμησης **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Επιστρέφει έναν πίνακα που περιέχει όλες τις τιμές του συγκεκριμένου τύπου απαρίθμησης. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Επιστρέφει ένα αντικείμενο που αντιπροσωπεύει μια τιμή της σταθεράς της απαρίθμησης του συγκεκριμένου τύπου με το συγκεκριμένο όνομα. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Μετατρέπει τη συγκεκριμένη τιμή 64-bit unsigned integer σε μέλος της απαρίθμησης. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Μετατρέπει το συγκεκριμένο αντικείμενο με ακέραια τιμή σε μέλος της απαρίθμησης. |
| virtual  [~EnumValues](./~enumvalues/)() | Καταστροφέας. |

## Δείτε επίσης

* Κλάση [EnumValuesBase](../enumvaluesbase/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)