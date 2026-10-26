---
title: Write()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εάν η λειτουργία περιτύλιξης είναι δυαδική, γράφει στη ροή το καθορισμένο υποεύρος bytes από τον καθορισμένο πίνακα bytes, διαφορετικά μετατρέπει το καθορισμένο υποεύρος bytes από τον καθορισμένο πίνακα bytes σε τύπο char_type και έπειτα γράφει το αποτέλεσμα στη ροή. Δεν υποστηρίζεται!
type: docs
weight: 79
url: /el/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Εάν η λειτουργία περιτύλιξης είναι δυαδική, γράφει στη ροή το καθορισμένο υπο-εύρος bytes από τον καθορισμένο πίνακα bytes· διαφορετικά μετατρέπει το καθορισμένο υπο-εύρος bytes από τον καθορισμένο πίνακα bytes σε τύπο char_type και έπειτα γράφει το αποτέλεσμα στη ροή. Δεν υποστηρίζεται!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα bytes προς εγγραφή. |
| offset | **int32_t** | Ένας δείκτης που αρχίζει από 0 του στοιχείου στο **buffer** όπου ξεκινά η υπο-περιοχή για εγγραφή. |
| count | **int32_t** | Ο αριθμός των στοιχείων στην υπο-περιοχή που θα εγγραφούν. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Γράφει το καθορισμένο υπο-εύρος bytes από τον καθορισμένο πίνακα bytes στη ροή.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα που περιέχει τα bytes προς εγγραφή |
| offset | **int32_t** | Ένας δείκτης που αρχίζει από 0 του στοιχείου στο **buffer** όπου ξεκινά η υπο-περιοχή για εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στην υπο-περιοχή που θα εγγραφούν |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)