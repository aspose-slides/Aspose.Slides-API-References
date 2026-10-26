---
title: VerifyHash()
second_title: مرجع API Aspose.Slides برای C++
description: امضای داده را بررسی می‌کند.
type: docs
weight: 118
url: /fa/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) متد

امضای داده‌ها را بررسی می‌کند.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | هش محاسبه‌شده برای داده‌های دریافت‌شده. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | امضا به‌صورت دریافت‌شده. |

### مقدار بازگشت

درست اگر امضا معتبر باشد، در غیر این صورت نادرست.

## موارد مرتبط

* تعریف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* کلاس [ECDsa](../)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)