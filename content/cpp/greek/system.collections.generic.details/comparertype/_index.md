---
title: ComparerType
second_title: Aspose.Slides για την Αναφορά API C++
description: Συγκρίνει στοιχεία χρησιμοποιώντας τη σημασιολογία 'less'.
type: docs
weight: 144
url: /el/system.collections.generic.details/comparertype/
---
## ComparerType struct

Συγκρίνει στοιχεία χρησιμοποιώντας τη σημασιολογία 'less'.

```cpp
template<typename T>class ComparerType
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος των συγκρινόμενων στοιχείων. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Συγκρίνει τύπους τιμών που υλοποιούν τη διασύνδεση [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Συγκρίνει τους πρωτόγονους τύπους τιμών και τα αντικείμενα που δεν υλοποιούν τη διασύνδεση [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Συγκρίνει τύπους κινητής υποδιαστολής. |

## Δείτε επίσης

* Χώρος ονομάτων [System::Collections::Generic::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)