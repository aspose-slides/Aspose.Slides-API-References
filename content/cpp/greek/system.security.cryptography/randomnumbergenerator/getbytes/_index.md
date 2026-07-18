---
title: GetBytes()
second_title: Aspose.Slides για C++ Αναφορά API
description: Συμπληρώνει τα υπάρχοντα στοιχεία του πίνακα με τυχαία bytes.
type: docs
weight: 14
url: /el/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) μέθοδος

Συμπληρώνει τα υπάρχοντα στοιχεία του πίνακα με τυχαία bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Διάταξη bytes για γέμισμα. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) μέθοδος

Συμπληρώνει το υπάρχον τμήμα του πίνακα με τυχαία bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Διάταξη bytes για γέμισμα τμήματος. |
| offset | int | Δείκτης έναρξης τμήματος. |
| count | int | Μέγεθος τμήματος. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) μέθοδος

Συμπληρώνει τα υπάρχοντα στοιχεία προβολής πίνακα με τυχαία bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Προβολή διάταξης bytes για γέμισμα. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) μέθοδος

Συμπληρώνει το υπάρχον τμήμα προβολής πίνακα με τυχαία bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Προβολή διάταξης bytes για γέμισμα τμήματος. |
| offset | int | Δείκτης έναρξης τμήματος. |
| count | int | Μέγεθος τμήματος. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) μέθοδος

Συμπληρώνει τα υπάρχοντα στοιχεία στοίβας πίνακα με τυχαία bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Στοίβα διάταξης bytes για γέμισμα. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) μέθοδος

Συμπληρώνει το υπάρχον τμήμα στοίβας πίνακα με τυχαία bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Στοίβα διάταξης bytes για γέμισμα τμήματος. |
| offset | int | Δείκτης έναρξης τμήματος. |
| count | int | Μέγεθος τμήματος. |

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RandomNumberGenerator](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)