---
title: GetBytes()
second_title: Aspose.Slides C++ API Referencia
description: Feltölti a meglévő tömb elemeit véletlenszerű bájtokkal.
type: docs
weight: 14
url: /hu/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) metódus

Feltölti a meglévő tömb elemeit véletlenszerű bájtokkal.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A kitöltendő bájt tömb. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) metódus

Feltölti a meglévő tömb szeletet véletlenszerű bájtokkal.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A szelet kitöltéséhez használandó bájt tömb. |
| offset | int | A szelet kezdő indexe. |
| count | int | A szelet mérete. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) metódus

Feltölti a meglévő tömb nézet elemeit véletlenszerű bájtokkal.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | A kitöltendő bájt tömb nézet. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) metódus

Feltölti a meglévő tömb nézet szeletet véletlenszerű bájtokkal.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | A szelet kitöltéséhez használandó bájt tömb nézet. |
| offset | int | A szelet kezdő indexe. |
| count | int | A szelet mérete. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) metódus

Feltölti a meglévő verem tömb elemeit véletlenszerű bájtokkal.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | A kitöltendő bájt verem tömb. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) metódus

Feltölti a meglévő verem tömb szeletet véletlenszerű bájtokkal.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | A szelet kitöltéséhez használandó bájt verem tömb. |
| offset | int | A szelet kezdő indexe. |
| count | int | A szelet mérete. |

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [RandomNumberGenerator](../)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)