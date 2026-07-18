---
title: Write()
second_title: Aspose.Slides για C++ API Αναφορά
description: Γράφει το καθορισμένο υποσύνολο των byte από τον καθορισμένο πίνακα byte στη ροή.
type: docs
weight: 209
url: /el/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Γράφει το καθορισμένο υποσύνολο των byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ο πίνακας που περιέχει τα byte προς εγγραφή. |
| offset | **int32_t** | Η μετατόπιση σε byte στον καθορισμένο πίνακα. |
| size | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) μέθοδος


Γράφει το καθορισμένο υποσύνολο των byte από τον καθορισμένο πίνακα byte στη ροή.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Η όψη του πίνακα που περιέχει τα byte προς εγγραφή |
| offset | **int32_t** | Ένας δείκτης που αρχίζει από 0 του στοιχείου στο **buffer** όπου αρχίζει το υποσύνολο προς εγγραφή |
| size | **int32_t** | Ο αριθμός των στοιχείων στο υποσύνολο προς εγγραφή |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [NetworkStream](../)
* Χώρος ονομάτων [System::Net::Sockets](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)