---
title: VerifyHash()
second_title: مرجع API Aspose.Slides برای C++
description: امضای داده‌ها را بررسی می‌کند.
type: docs
weight: 222
url: /fa/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) متد

امضای داده‌ها را بررسی می‌کند.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | هش محاسبه‌شده برای داده‌های دریافت‌شده. |
| str | const [String](../../../system/string/)\& | نام الگوریتم هش استفاده‌شده. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | امضای دریافت‌شده. |

### مقدار بازگشت

درست اگر امضا معتبر باشد، در غیر این صورت غلط.

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [DSACryptoServiceProvider](../)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)