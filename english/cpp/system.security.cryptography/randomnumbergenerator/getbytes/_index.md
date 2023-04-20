---
title: GetBytes()
second_title: Aspose.Slides for C++ API Reference
description: Fills existing array elements with random bytes.
type: docs
weight: 14
url: /cpp/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) method


Fills existing array elements with random bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes array to fill. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) method


Fills existing array slice with random bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes array to fill slice of. |
| offset | int | Slice beginning index. |
| count | int | Slice size. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) method


Fills existing array view elements with random bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Bytes array view to fill. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) method


Fills existing array view slice with random bytes.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | Bytes array view to fill slice of. |
| offset | int | Slice beginning index. |
| count | int | Slice size. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) method


Fills existing stack array elements with random bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Bytes stack array to fill. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) method


Fills existing stack array slice with random bytes.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | Bytes stack array to fill slice of. |
| offset | int | Slice beginning index. |
| count | int | Slice size. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RandomNumberGenerator](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)