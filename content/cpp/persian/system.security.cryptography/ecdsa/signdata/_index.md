---
title: SignData()
second_title: Aspose.Slides برای مرجع API C++
description: مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌دارد.
type: docs
weight: 79
url: /fa/system.security.cryptography/ecdsa/signdata/
---
## ECDsa::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌دارد.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه دادهٔ ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. امضای ECDSA را برای دادهٔ ورودی برمی‌گرداند. |

## ECDsa::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌دارد.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه دادهٔ ورودی. |
| offset | **int32_t** | افست در **data**. |
| count | **int32_t** | تعداد بایت‌های مورد استفاده به عنوان دادهٔ ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. امضای ECDSA را برای دادهٔ ورودی برمی‌گرداند. |

## ECDsa::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

مقدار هش جریان باینری مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌دارد.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توصیف |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | جریان باینری. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. امضای ECDSA را برای دادهٔ ورودی برمی‌گرداند. |

## مراجع

* تعریف‌نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعریف‌نوع [StreamPtr](../../../system/streamptr/)
* کلاس [ECDsa](../)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)