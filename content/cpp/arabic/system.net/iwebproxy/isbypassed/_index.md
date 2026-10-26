---
title: IsBypassed()
second_title: مرجع API Aspose.Slides للغة C++
description: إرجاع قيمة تشير إلى ما إذا كان يجب عدم استخدام الوكيل للمضيف المحدد.
type: docs
weight: 40
url: /ar/system.net/iwebproxy/isbypassed/
---
## IWebProxy::IsBypassed(System::SharedPtr\<Uri\>) طريقة


Returns a value that indicates if the proxy must not be used for the specified host.

```cpp
virtual bool System::Net::IWebProxy::IsBypassed(System::SharedPtr<Uri> host)=0
```


### الوسائط

| المعامِل | النوع | الوصف |
| --- | --- | --- |
| host | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | معرّف URI للمضيف المراد فحصه. |

### Return Value

True عندما لا يجب استخدام خادم الوكيل، وإلا false.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [IWebProxy](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)