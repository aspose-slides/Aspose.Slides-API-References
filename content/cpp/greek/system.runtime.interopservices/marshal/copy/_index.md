---
title: Copy()
second_title: Aspose.Slides για C++ API Αναφορά
description: Υλοποιεί τη σημασιολογία public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics.
type: docs
weight: 1
url: /el/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) μέθοδος

Υλοποιεί public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| container | Τύπος προορισμού του container. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | const IntPtr | Δείκτης δεδομένων προέλευσης. |
| destination | container\&& | Container στον οποίο αντιγράφονται τα δεδομένα. |
| startIndex | int | Δείκτης έναρξης προέλευσης. |
| length | int | Αριθμός στοιχείων προς αντιγραφή. |

## Marshal::Copy(const void *, container\&&, int, int) μέθοδος

Υλοποιεί public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantics.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| container | Τύπος προορισμού του container. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | const void * | Δείκτης δεδομένων προέλευσης. |
| destination | container\&& | Container στον οποίο αντιγράφονται τα δεδομένα. |
| startIndex | int | Δείκτης έναρξης προέλευσης. |
| length | int | Αριθμός στοιχείων προς αντιγραφή. |

## Marshal::Copy(const container\&, int, void *, int) μέθοδος

Υλοποιεί public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| container | Τύπος προέλευσης του container. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | const container\& | Δείκτης δεδομένων προέλευσης. |
| startIndex | int | Δείκτης έναρξης προέλευσης. |
| destination | void * | Δείκτης δεδομένων προορισμού. |
| length | int | Αριθμός στοιχείων προς αντιγραφή. |

## Marshal::Copy(const container\&, int, IntPtr, int) μέθοδος

Υλοποιεί public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| container | Τύπος προέλευσης του container. |

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| source | const container\& | Δείκτης δεδομένων προέλευσης. |
| startIndex | int | Δείκτης έναρξης προέλευσης. |
| destination | IntPtr | Δείκτης δεδομένων προορισμού. |
| length | int | Αριθμός στοιχείων προς αντιγραφή. |

## Δείτε επίσης

* Κλάση [Marshal](../)
* Χώρος ονομάτων [System::Runtime::InteropServices](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)