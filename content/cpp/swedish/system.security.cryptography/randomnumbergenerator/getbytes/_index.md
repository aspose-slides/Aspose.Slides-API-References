---
title: GetBytes()
second_title: Aspose.Slides för C++ API-referens
description: Fyller befintliga array-element med slumpmässiga byte.
type: docs
weight: 14
url: /sv/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) metod

Fyller befintliga array-element med slumpmässiga byte.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-array att fylla. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) metod

Fyller en befintlig del av array med slumpmässiga byte.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte-array att fylla del av. |
| offset | int | Index för delens början. |
| count | int | Delens storlek. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) metod

Fyller befintliga arrayvy-element med slumpmässiga byte.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Byte-arrayvy att fylla. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) metod

Fyller en befintlig del av arrayvyn med slumpmässiga byte.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Byte-arrayvy att fylla del av. |
| offset | int | Index för delens början. |
| count | int | Delens storlek. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) metod

Fyller befintliga stack-array-element med slumpmässiga byte.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Byte stack-array att fylla. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) metod

Fyller en befintlig del av stack-array med slumpmässiga byte.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Byte stack-array att fylla del av. |
| offset | int | Index för delens början. |
| count | int | Delens storlek. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RandomNumberGenerator](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)