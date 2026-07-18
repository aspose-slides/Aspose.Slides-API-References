---
title: GetByte()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ανακτά την τιμή byte στη συγκεκριμένη θέση byte.
type: docs
weight: 27
url: /el/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) μέθοδος

Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ανακτά την τιμή byte στη συγκεκριμένη θέση byte.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Ο στόχος πίνακας |
| index | int | Μετατόπιση με βάση το μηδέν του byte που θα ανακτηθεί |

### Τιμή επιστροφής

Η τιμή byte στη συγκεκριμένη θέση

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) μέθοδος

Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ανακτά την τιμή byte στη συγκεκριμένη θέση byte.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων της προβολής πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Η στόχος προβολή πίνακα |
| index | int | Μετατόπιση με βάση το μηδέν του byte που θα ανακτηθεί |

### Τιμή επιστροφής

Η τιμή byte στη συγκεκριμένη θέση

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) μέθοδος

Ερμηνεύει τον καθορισμένο τύπο πίνακα ως ακατέργαστο πίνακα byte και ανακτά την τιμή byte στη συγκεκριμένη θέση byte.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του στοίβας πίνακα |
| N | Το μέγεθος του στοίβας πίνακα |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Η στόχος στοίβας πίνακα |
| index | int | Μετατόπιση με βάση το μηδέν του byte που θα ανακτηθεί |

### Τιμή επιστροφής

Η τιμή byte στη συγκεκριμένη θέση

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Array](../../array/)
* Κλάση [Buffer](../)
* Χώρος ονομάτων [System](../../)
* Library [Aspose.Slides](../../../)