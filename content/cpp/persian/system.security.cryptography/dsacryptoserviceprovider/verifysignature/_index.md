---
title: VerifySignature()
second_title: Aspose.Slides برای C++ مرجع API
description: امضای DSA را برای دادهٔ مشخص شده تأیید کنید.
type: docs
weight: 118
url: /fa/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) متد

امضای [DSA](../../dsa/) را برای دادهٔ مشخص شده تأیید کنید.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) با **rgb_signature** امضا شده. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) امضا. |

### مقدار بازگشت

true - اگر **rgb_signature** با امضای [DSA](../../dsa/) محاسبه شده روی **rgb_hash** مطابقت داشته باشد، در غیر این صورت - false.

## مراجع

* تعریف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* کلاس [DSACryptoServiceProvider](../)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)