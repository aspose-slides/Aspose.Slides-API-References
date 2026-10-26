---
title: VerifySignature()
second_title: مرجع API Aspose.Slides برای C++
description: امضای هش داده را تأیید می‌کند.
type: docs
weight: 40
url: /fa/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

امضای هش داده را تأیید می‌کند.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | هشی که برای داده محاسبه شده است. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | امضای دریافت‌شده برای داده. |

### مقدار بازگشت

درست اگر امضا معتبر باشد، در غیر این صورت نادرست.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [RSAPKCS1SignatureDeformatter](../)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)