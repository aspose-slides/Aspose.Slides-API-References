---
title: IsStringByteSequence
second_title: Aspose.Slides για C++ API Αναφορά
description: Μαγεία προτύπου για να ελέγξει αν ένας τύπος είναι μια ακολουθία χαρακτήρων συμβολοσειράς.
type: docs
weight: 1691
url: /el/system/isstringbytesequence/
---
## IsStringByteSequence struct

Μαγεία προτύπου για να ελέγξει αν ένας τύπος είναι μια ακολουθία χαρακτήρων συμβολοσειράς.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος που ελέγχεται. |
| CharT | Τύπος χαρακτήρα για έλεγχο. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)