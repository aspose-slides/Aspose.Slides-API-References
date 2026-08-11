---
title: HashData()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند.
type: docs
weight: 105
url: /fa/system.security.cryptography/ecdsabotan/hashdata/
---
## ECDsaBotan::HashData(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) متد

مقدار هش داده‌های مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(ByteArrayPtr data, int32_t offset, int32_t count, HashAlgorithmName hash_algorithm) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) برای هش کردن. |
| offset | **int32_t** | مقدار جابجایی در **data**. |
| count | **int32_t** | تعداد بایت‌ها برای هش کردن. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | الگوریتم هش. |

### مقدار بازگشتی

داده‌های هش‌شده.

## ECDsaBotan::HashData(StreamPtr, HashAlgorithmName) متد

مقدار هش جریان باینری مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::HashData(StreamPtr stream, HashAlgorithmName hash_algorithm) override
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [StreamPtr](../../../system/streamptr/) | جریان باینری برای هش شدن. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | الگوریتم هش. |

### مقدار بازگشتی

داده‌های هش‌شده.

## موارد مرتبط

* تعریف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعریف نوع [StreamPtr](../../../system/streamptr/)
* کلاس [ECDsaBotan](../)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)