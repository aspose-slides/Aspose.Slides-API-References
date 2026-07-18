---
title: SetByte()
second_title: Αναφορά API Aspose.Slides για C++
description: Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ορίζει την καθορισμένη τιμή byte στη συγκεκριμένη μετατόπιση byte.
type: docs
weight: 40
url: /el/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) μέθοδος


Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ορίζει την καθορισμένη τιμή byte στη συγκεκριμένη μετατόπιση byte.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Ο πίνακας προορισμού |
| index | int | Μετατόπιση byte που θα οριστεί, με βάση το μηδέν |
| value | **uint8_t** | Η τιμή byte που θα οριστεί |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) μέθοδος


Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ορίζει την καθορισμένη τιμή byte στη συγκεκριμένη μετατόπιση byte.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Η προβολή του πίνακα προορισμού |
| index | int | Μετατόπιση byte που θα οριστεί, με βάση το μηδέν |
| value | **uint8_t** | Η τιμή byte που θα οριστεί |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) μέθοδος


Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ορίζει την καθορισμένη τιμή byte στη συγκεκριμένη μετατόπιση byte.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```


### Παράμετροι προτύπων

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του πίνακα |
| N | Το μέγεθος του στοίβας πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Ο στοίβας πίνακας προορισμού |
| index | int | Μετατόπιση byte που θα οριστεί, με βάση το μηδέν |
| value | **uint8_t** | Η τιμή byte που θα οριστεί |

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Array](../../array/)
* Κλάση [Buffer](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)