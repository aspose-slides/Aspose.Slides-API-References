---
title: VerifySignature()
second_title: Aspose.Slides برای C++ مرجع API
description: امضای DSA را برای دادهٔ مشخص‌شده تأیید می‌کند.
type: docs
weight: 14
url: /fa/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) متد

امضای [DSA](../) را برای دادهٔ مشخص‌شده تأیید کنید.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) امضا شده با **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) امضا. |

### مقدار بازگشت
true - اگر **rgb_signature** با امضای [DSA](../) که بر روی **rgb_hash** محاسبه شده است مطابقت داشته باشد، در غیر این صورت - false.

## مراجع

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* کلاس [DSA](../)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)