---
title: ComputeHash()
second_title: مرجع API Aspose.Slides برای C++
description: بافر را هش می‌کند.
type: docs
weight: 14
url: /fa/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) متد

هش بافر.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بافر منبع. |

### مقدار بازگشت

مقدار هش محاسبه‌شده.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) متد

هش برش بافر.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | بافر منبع. |
| offset | int | آفست در بافر منبع. |
| count | int | تعداد بایت‌های مورد استفاده از بافر منبع. |

### مقدار بازگشت

مقدار هش محاسبه‌شده.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) متد

جریان را تا انتها می‌خواند و هش داده‌های خوانده‌شده را محاسبه می‌کند.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | جریانی برای خواندن داده‌ها. |

### مقدار بازگشت

مقدار هش محاسبه‌شده برای تمام داده‌های جریان.

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [HashAlgorithm](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)