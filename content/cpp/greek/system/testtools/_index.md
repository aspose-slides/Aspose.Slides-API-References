---
title: TestTools
second_title: Aspose.Slides για C++ API Αναφορά
description: Παρέχει ένα σύνολο χρήσιμων μεθόδων που ελέγχουν ορισμένες βασικές ιδιότητες διαφόρων τύπων και συναρτήσεων.
type: docs
weight: 1899
url: /el/system/testtools/
---
## TestTools struct

Παρέχει ένα σύνολο χρήσιμων μεθόδων που ελέγχουν ορισμένες βασικές ιδιότητες διαφόρων τύπων και συναρτήσεων.

```cpp
class TestTools
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Ελέγχει εάν η συνάρτηση ρίχνει εξαίρεση οποιουδήποτε τύπου. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Ελέγχει εάν η συμβολοσειρά είναι κενή. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Ελέγχει εάν η συλλογή είναι κενή. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Ελέγχει εάν η συγκεκριμένη τιμή είναι null. [Version](../version/) για αριθμητικούς και enum τύπους. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Ελέγχει εάν η συγκεκριμένη τιμή είναι null. [Version](../version/) για μη αριθμητικούς και μη enum τύπους τιμών. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Ελέγχει εάν η συγκεκριμένη τιμή είναι null. [Version](../version/) για μη αριθμητικούς τύπους τιμών. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Ελέγχει εάν η συγκεκριμένη τιμή είναι null. [Version](../version/) για ζεύγη κλειδιού-τιμής. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Ελέγχει εάν η συμβολοσειρά είναι null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Ελέγχει εάν η συλλογή είναι null ή κενή. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Ελέγχει εάν η συμβολοσειρά είναι null ή κενή. |
## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)