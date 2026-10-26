---
title: GetBytes()
second_title: Aspose.Slides برای مرجع API C++
description: عناصر موجود آرایه را با بایت‌های تصادفی پر می‌کند.
type: docs
weight: 14
url: /fa/system.security.cryptography/randomnumbergenerator/getbytes/
---
## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>) متد

عناصر موجود آرایه را با بایت‌های تصادفی پر می‌کند.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایت برای پر کردن. |

## RandomNumberGenerator::GetBytes(ArrayPtr\<uint8_t\>, int, int) متد

بخش موجود آرایه را با بایت‌های تصادفی پر می‌کند.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(ArrayPtr<uint8_t> bytes, int offset, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | آرایه بایت برای پر کردن بخش از. |
| offset | int | شاخص آغاز بخش. |
| count | int | اندازه بخش. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>) متد

عناصر موجود نمای آرایه را با بایت‌های تصادفی پر می‌کند.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | نمای آرایه بایت برای پر کردن. |

## RandomNumberGenerator::GetBytes(System::Details::ArrayView\<uint8_t\>, int, int) متد

بخش موجود نمای آرایه را با بایت‌های تصادفی پر می‌کند.

```cpp
virtual void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::ArrayView<uint8_t> bytes, int offset, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | System::Details::ArrayView\<**uint8_t**\> | نمای آرایه بایت برای پر کردن بخش از. |
| offset | int | شاخص آغاز بخش. |
| count | int | اندازه بخش. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&) متد

عناصر موجود آرایه پشته را با بایت‌های تصادفی پر می‌کند.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه پشته بایت برای پر کردن. |

## RandomNumberGenerator::GetBytes(System::Details::StackArray\<uint8_t, N\>\&, int, int) متد

بخش موجود آرایه پشته را با بایت‌های تصادفی پر می‌کند.

```cpp
template<std::size_t> void System::Security::Cryptography::RandomNumberGenerator::GetBytes(System::Details::StackArray<uint8_t, N> &bytes, int offset, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | آرایه پشته بایت برای پر کردن بخش از. |
| offset | int | شاخص آغاز بخش. |
| count | int | اندازه بخش. |

## همچنین ببینید

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [RandomNumberGenerator](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)