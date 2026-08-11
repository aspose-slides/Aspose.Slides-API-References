---
title: VerifyData()
second_title: مرجع API Aspose.Slides للـ C++
description: يفحص توقيع البيانات.
type: docs
weight: 209
url: /ar/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) method

يفحص توقيع البيانات.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) للتحقق من التوقيع. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | خوارزمية التجزئة المستخدمة. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | التوقيع كما تم استلامه. |

### قيمة الإرجاع

True إذا كان التوقيع صالحًا، false خلاف ذلك.

## انظر أيضًا

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* الصنف [Object](../../../system/object/)
* الصنف [RSACryptoServiceProvider](../)
* النطاق [System::Security::Cryptography](../../)
* المكتبة [Aspose.Slides](../../../)