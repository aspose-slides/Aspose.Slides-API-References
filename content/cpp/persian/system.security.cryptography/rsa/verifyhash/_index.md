---
title: VerifyHash()
second_title: مرجع API Aspose.Slides برای C++
description: تأیید می‌کند که امضای هش مشخص شده معتبر است.
type: docs
weight: 170
url: /fa/system.security.cryptography/rsa/verifyhash/
---
## RSA::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) متد

تایید می‌کند که امضای هش مشخص شده معتبر است.

```cpp
virtual bool System::Security::Cryptography::RSA::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | مقدار هش داده‌های امضا شده. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | داده‌های امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | حالت پرکردن. اگر امضا معتبر باشد true برگردانده می‌شود، در غیر این صورت false. |

## مراجع

* تعریف‌نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [RSASignaturePadding](../../rsasignaturepadding/)
* کلاس [RSA](../)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)