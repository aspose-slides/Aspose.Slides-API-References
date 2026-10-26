---
title: GetBytes()
second_title: Aspose.Slides für C++ API-Referenz
description: Füllt bestehende Array-Elemente mit zufälligen Bytes.
type: docs
weight: 14
url: /de/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) Methode

Füllt bestehende Array-Elemente mit zufälligen Bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-Array zum Füllen. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) Methode

Füllt bestehenden Array-Abschnitt mit zufälligen Bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-Array zum Füllen des Abschnitts. |
| offset | int | Anfangsindex des Abschnitts. |
| count | int | Größe des Abschnitts. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) Methode

Füllt bestehende Array-View-Elemente mit zufälligen Bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Byte-Array-View zum Füllen. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) Methode

Füllt bestehenden Array-View-Abschnitt mit zufälligen Bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Byte-Array-View zum Füllen des Abschnitts. |
| offset | int | Anfangsindex des Abschnitts. |
| count | int | Größe des Abschnitts. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) Methode

Füllt bestehende Stack-Array-Elemente mit zufälligen Bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Byte-Stack-Array zum Füllen. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) Methode

Füllt bestehenden Stack-Array-Abschnitt mit zufälligen Bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Byte-Stack-Array zum Füllen des Abschnitts. |
| offset | int | Anfangsindex des Abschnitts. |
| count | int | Größe des Abschnitts. |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [RandomNumberGenerator](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)