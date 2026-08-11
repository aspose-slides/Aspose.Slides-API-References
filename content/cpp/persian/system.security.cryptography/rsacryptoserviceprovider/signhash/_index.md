---
title: SignHash()
second_title: Aspose.Slides برای C++ مرجع API
description: امضا را برای مقدار هش مشخص‌شده محاسبه می‌کند.
type: docs
weight: 196
url: /fa/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) متد

امضا را برای مقدار هش مشخص‌شده محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | مقدار هش. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | الگوریتم هش. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | حالت پر شدن. امضای [RSA](../../rsa/) را برای هش مشخص‌شده برمی‌گرداند. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) متد

امضا را برای مقدار ورودی مشخص‌شده محاسبه می‌کند. پیاده‌سازی نشده است.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | مقدار هش داده‌ای که باید امضا شود. |
| str | const [String](../../../system/string/)\& | شناسه الگوریتم هش مورد استفاده برای ایجاد هش. |

### مقدار بازگشتی

[RSA](../../rsa/) امضای برای داده‌های مشخص‌شده.

## موارد مرتبط

* تعریف‌نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [RSASignaturePadding](../../rsasignaturepadding/)
* کلاس [RSACryptoServiceProvider](../)
* کلاس [String](../../../system/string/)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)