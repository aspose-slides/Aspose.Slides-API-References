---
title: GetBytes()
second_title: Aspose.Slides لـ C++ مرجع API
description: يملأ عناصر المصفوفة الحالية بالبايتات العشوائية.
type: docs
weight: 14
url: /ar/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) طريقة

يملأ عناصر المصفوفة الحالية بالبايتات العشوائية.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايتات للتعبئة. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) طريقة

يملأ شريحة المصفوفة الحالية بالبايتات العشوائية.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايتات لتعبئة الشريحة من. |
| offset | int | فهرس بداية الشريحة. |
| count | int | حجم الشريحة. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) طريقة

يملأ عناصر عرض المصفوفة الحالية بالبايتات العشوائية.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | عرض مصفوفة البايتات للتعبئة. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) طريقة

يملأ شريحة عرض المصفوفة الحالية بالبايتات العشوائية.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | عرض مصفوفة البايتات لتعبئة الشريحة من. |
| offset | int | فهرس بداية الشريحة. |
| count | int | حجم الشريحة. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) طريقة

يملأ عناصر مصفوفة المكدس الحالية بالبايتات العشوائية.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة مكدس البايتات للتعبئة. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) طريقة

يملأ شريحة مصفوفة المكدس الحالية بالبايتات العشوائية.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة مكدس البايتات لتعبئة الشريحة من. |
| offset | int | فهرس بداية الشريحة. |
| count | int | حجم الشريحة. |

## انظر أيضًا

* إعادة تعريف [ArrayPtr](../../../system/arrayptr/)
* فئة [RandomNumberGenerator](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)