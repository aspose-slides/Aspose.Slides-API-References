---
title: Write()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αν η λειτουργία περιτύλιξης είναι binary, γράφει στη ροή το καθορισμένο υποδιάστημα byte από τον καθορισμένο πίνακα byte, ενώ σε διαφορετική περίπτωση μετατρέπει το καθορισμένο υποδιάστημα byte από τον καθορισμένο πίνακα byte σε τύπο char_type και έπειτα γράφει το αποτέλεσμα στη ροή.
type: docs
weight: 79
url: /el/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Αν το mode συσκευασίας είναι binary, γράφει στη ροή το καθορισμένο υποδιάστημα byte από τον καθορισμένο πίνακα byte, διαφορετικά μετατρέπει το καθορισμένο υποδιάστημα byte από τον καθορισμένο πίνακα byte σε τύπο char_type και στη συνέχεια γράφει το αποτέλεσμα στη ροή.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Δείκτης 0-βάσης του στοιχείου στο **buffer** όπου αρχίζει το υποδιάστημα προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποδιάστημα προς εγγραφή |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υποδιάστημα byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Δείκτης 0-βάσης του στοιχείου στο **buffer** όπου αρχίζει το υποδιάστημα προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υποδιάστημα προς εγγραφή |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)