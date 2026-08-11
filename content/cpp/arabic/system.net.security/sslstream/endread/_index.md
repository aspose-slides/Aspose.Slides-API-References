---
title: EndRead()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة.
type: docs
weight: 430
url: /ar/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) طريقة


ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية قراءة غير متزامنة |

### قيمة الإرجاع

عدد البايتات التي تم قراءتها أثناء عملية القراءة التي تم تمثيلها بواسطة **asyncResult**

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [SslStream](../)
* مساحة الاسم [System::Net::Security](../../)
* مكتبة [Aspose.Slides](../../../)