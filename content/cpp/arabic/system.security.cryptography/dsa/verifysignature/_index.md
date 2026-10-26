---
title: VerifySignature()
second_title: Aspose.Slides لـ C++ مرجع API
description: تحقق من توقيع DSA للبيانات المحددة.
type: docs
weight: 14
url: /ar/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) طريقة

تحقق من توقيع [DSA](../) للبيانات المحددة.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) موقّع باستخدام **rgb_signature**. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) التوقيع. |

### قيمة الإرجاع

true - إذا كان **rgb_signature** يطابق توقيع [DSA](../) المُحسوب على **rgb_hash**, وإلا - false.

## انظر أيضًا

* تعريف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* فئة [DSA](../)
* مساحة الاسم [System::Security::Cryptography](../../)
* مكتبة [Aspose.Slides](../../../)