---
title: VerifyHash()
second_title: مرجع API Aspose.Slides برای C++
description: امضای داده‌ها را بررسی می‌کند.
type: docs
weight: 222
url: /fa/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) method

امضای داده‌ها را بررسی می‌کند.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | هش محاسبه‌شده برای داده‌های دریافت‌شده. |
| str | const [String](../../../system/string/)\& | نام الگوریتم هش مورد استفاده. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | امضا به‌همین شکل دریافت شده. |

### مقدار بازگشت

درست اگر امضا معتبر باشد، در غیر این صورت غلط.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) method

تایید می‌کند که امضای هش مشخص‌شده معتبر است.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | مقدار هش داده‌های امضاشده. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | داده‌ی امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | حالت padding. در صورت اعتبار امضا true برگردانده می‌شود، در غیر این صورت false. |

## موارد مرتبط

* تعریف‌نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [RSACryptoServiceProvider](../)
* کلاس [RSASignaturePadding](../../rsasignaturepadding/)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)