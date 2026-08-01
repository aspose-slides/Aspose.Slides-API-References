---
title: GetBytes()
second_title: Aspose.Slides voor C++ API-referentie
description: Vult bestaande array-elementen met willekeurige bytes.
type: docs
weight: 14
url: /nl/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) methode

Vult bestaande array-elementen met willekeurige bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes-array om te vullen. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) methode

Vult een bestaand gedeelte van een array met willekeurige bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes-array om deel van te vullen. |
| offset | int | Beginindex van de slice. |
| count | int | Grootte van de slice. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) methode

Vult bestaande array-view-elementen met willekeurige bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Bytes-array-view om te vullen. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) methode

Vult een bestaand gedeelte van een array-view met willekeurige bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Bytes-array-view om deel van te vullen. |
| offset | int | Beginindex van de slice. |
| count | int | Grootte van de slice. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) methode

Vult bestaande stack-array-elementen met willekeurige bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Bytes-stack-array om te vullen. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) methode

Vult een bestaand gedeelte van een stack-array met willekeurige bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Bytes-stack-array om deel van te vullen. |
| offset | int | Beginindex van de slice. |
| count | int | Grootte van de slice. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [RandomNumberGenerator](../)
* Namespace [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)