---
title: ByteLength()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Καθορίζει τον αριθμό των byte που καταλαμβάνονται από όλα τα στοιχεία του συγκεκριμένου πίνακα.
type: docs
weight: 14
url: /el/system/buffer/bytelength/
---
## Buffer::ByteLength(const SharedPtr\<Array\<T\>\>\&) μέθοδος


Καθορίζει τον αριθμό των byte που καταλαμβάνονται από όλα τα στοιχεία του συγκεκριμένου πίνακα.

```cpp
template<class T> static int System::Buffer::ByteLength(const SharedPtr<Array<T>> &array)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | Ένας πίνακας |

### Τιμή επιστροφής

Ο αριθμός των byte που καταλαμβάνονται από όλα τα στοιχεία του συγκεκριμένου πίνακα

## Buffer::ByteLength(const System::Details::ArrayView\<T\>\&) μέθοδος


Καθορίζει τον αριθμό των byte που καταλαμβάνονται από όλα τα στοιχεία του συγκεκριμένου φάσματος πίνακα.

```cpp
template<class T> static int System::Buffer::ByteLength(const System::Details::ArrayView<T> &array)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του φάσματος πίνακα |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | Ένα φάσμα πίνακα |

### Τιμή επιστροφής

Ο αριθμός των byte που καταλαμβάνονται από όλα τα στοιχεία του συγκεκριμένου φάσματος πίνακα

## Buffer::ByteLength(const System::Details::StackArray\<T, N\>\&) μέθοδος


Καθορίζει τον αριθμό των byte που καταλαμβάνονται από όλα τα στοιχεία του συγκεκριμένου πίνακα στοίβας.

```cpp
template<class T,std::size_t> static int System::Buffer::ByteLength(const System::Details::StackArray<T, N> &array)
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος των στοιχείων του πίνακα στοίβας |
| N | Το μέγεθος του πίνακα στοίβας |

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | Μια στοίβα πίνακα |

### Τιμή επιστροφής

Ο αριθμός των byte που καταλαμβάνονται από όλα τα στοιχεία του συγκεκριμένου πίνακα στοίβας

## Δείτε επίσης

* Typedef [SharedPtr](../../sharedptr/)
* Κλάση [Array](../../array/)
* Κλάση [Buffer](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)