---
title: Compare()
second_title: Aspose.Slides για την αναφορά API C++
description: Συγκρίνει δύο έξυπνους δείκτες.
type: docs
weight: 1
url: /el/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) συνάρτηση

Συγκρίνει δύο έξυπνους δείκτες.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος του πρώτου έξυπνου δείκτη |
| U | Τύπος του δεύτερου έξυπνου δείκτη |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Πρώτος έξυπνος δείκτης |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Δεύτερος έξυπνος δείκτης |

### Τιμή επιστροφής

[Comparison](../../system/comparison/) αποτέλεσμα (0 αν είναι ίσοι, -1 αν a < b, 1 αν a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) συνάρτηση

Συγκρίνει δύο αριθμητικές τιμές.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Αριθμητικός τύπος |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const T\& | Πρώτη τιμή |
| b | const T\& | Δεύτερη τιμή |

### Τιμή επιστροφής

[Comparison](../../system/comparison/) αποτέλεσμα (0 αν είναι ίσοι, -1 αν a < b, 1 αν a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) συνάρτηση

Συγκρίνει έναν έξυπνο δείκτη με μια τιμή.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος στον οποίο δείχνει ο έξυπνος δείκτης |
| U | Τύπος της τιμής |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Έξυπνος δείκτης |
| b | const U\& | Τιμή |

### Τιμή επιστροφής

[Comparison](../../system/comparison/) αποτέλεσμα (0 αν είναι ίσοι, -1 αν a < b, 1 αν a > b)

## Δείτε επίσης

* Typedef [SharedPtr](../../system/sharedptr/)
* Χώρος ονομάτων [System::MemoryExtensions::Details](../)
* Βιβλιοθήκη [Aspose.Slides](../../)