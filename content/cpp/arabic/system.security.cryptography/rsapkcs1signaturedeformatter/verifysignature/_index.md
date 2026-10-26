---
title: VerifySignature()
second_title: مرجع API Aspose.Slides للغة C++
description: يتحقق من توقيع تجزئة البيانات.
type: docs
weight: 40
url: /ar/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) طريقة

يتحقق من توقيع تجزئة البيانات.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | التجزئة المحسوبة للبيانات. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | التوافق المستلم للبيانات. |

### Return Value

صحيح إذا كان التوقيع صالحًا، خطأ خلاف ذلك.

## See Also

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [RSAPKCS1SignatureDeformatter](../)
* نطاق [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)