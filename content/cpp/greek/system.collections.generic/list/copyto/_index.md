---
title: CopyTo()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιγράφει τα στοιχεία της λίστας σε υπάρχοντα στοιχεία του πίνακα.
type: docs
weight: 209
url: /el/system.collections.generic/list/copyto/
---
## List::CopyTo(System::ArrayPtr\<T\>, int) μέθοδος

Αντιγράφει τα στοιχεία της λίστας σε υπάρχοντα στοιχεία του πίνακα.

```cpp
void System::Collections::Generic::List<T>::CopyTo(System::ArrayPtr<T> array, int arrayIndex) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<T\> | Πίνακας προορισμού. |
| arrayIndex | int | Αρχικός δείκτης του πίνακα προορισμού. |

## List::CopyTo(const System::ArrayPtr\<T\>\&) μέθοδος

Αντιγράφει όλα τα στοιχεία σε υπάρχοντα στοιχεία του πίνακα.

```cpp
void System::Collections::Generic::List<T>::CopyTo(const System::ArrayPtr<T> &array)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) για αντιγραφή στοιχείων μέσα. |

## List::CopyTo(int, const System::ArrayPtr\<T\>\&, int, int) μέθοδος

Αντιγράφει στοιχεία ξεκινώντας από τον καθορισμένο δείκτη σε υπάρχοντα στοιχεία του πίνακα.

```cpp
void System::Collections::Generic::List<T>::CopyTo(int index, const System::ArrayPtr<T> &array, int arrayIndex, int count)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | int | Ένας 0-βάση δείκτης του στοιχείου στη λίστα που αντιπροσωπεύεται από το τρέχον αντικείμενο, από τον οποίο ξεκινά η αντιγραφή. |
| array | const [System::ArrayPtr](../../../system/arrayptr/)\<T\>\& | [Array](../../../system/array/) για αντιγραφή στοιχείων μέσα. |
| arrayIndex | int | Αρχική θέση στον πίνακα προορισμού. |
| count | int | Αριθμός στοιχείων προς αντιγραφή. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [List](../)
* Χώρος ονομάτων [System::Collections::Generic](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)