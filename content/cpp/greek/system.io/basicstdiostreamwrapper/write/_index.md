---
title: Write()
second_title: Aspose.Slides για C++ API Reference
description: Εάν η λειτουργία περιτύλιξης είναι δυαδική, γράφει στη ροή το καθορισμένο υπο-εύρος των byte από τον καθορισμένο πίνακα byte· διαφορετικά, μετατρέπει το καθορισμένο υπο-εύρος των byte από τον καθορισμένο πίνακα byte σε τύπο char_type και στη συνέχεια γράφει το αποτέλεσμα στη ροή.
type: docs
weight: 79
url: /el/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Εάν η λειτουργία περιτύλιξης είναι δυαδική, γράφει στη ροή το καθορισμένο υπο-εύρος των byte από τον καθορισμένο πίνακα byte, διαφορετικά μετατρέπει το καθορισμένο υπο-εύρος των byte από τον καθορισμένο πίνακα byte στον τύπο char_type και έπειτα γράφει το αποτέλεσμα στη ροή.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Ένδειξη 0-βάσης του στοιχείου στο **buffer** στην οποία ξεκινά το υπο-εύρος προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υπο-εύρος προς εγγραφή |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος

Γράφει το καθορισμένο υπο-εύρος των byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η προβολή πίνακα που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Ένδειξη 0-βάσης του στοιχείου στο **buffer** στην οποία ξεκινά το υπο-εύρος προς εγγραφή |
| count | **int32_t** | Ο αριθμός των στοιχείων στο υπο-εύρος προς εγγραφή |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [BasicSTDIOStreamWrapper](../)
* Χώρος ονομάτων [System::IO](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)