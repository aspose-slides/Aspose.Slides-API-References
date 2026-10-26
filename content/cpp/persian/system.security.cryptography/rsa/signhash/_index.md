---
title: SignHash()
second_title: مرجع API Aspose.Slides برای C++
description: امضای مقدار هش مشخص‌شده را محاسبه می‌کند.
type: docs
weight: 144
url: /fa/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) متد

امضا را برای مقدار هش مشخص‌شده محاسبه می‌کند.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | مقدار هش. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | الگوریتم هش. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | حالت padding. بازگرداندن [RSA](../) امضا برای هش مشخص‌شده. |

## موارد مرتبط

* تعریف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [RSASignaturePadding](../../rsasignaturepadding/)
* کلاس [RSA](../)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)