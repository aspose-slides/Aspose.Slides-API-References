---
title: IsMustUnderstandFaultCode()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که آیا کد مشخص‌شده برابر با کد خطای SOAP 'MustUnderstand' است یا خیر.
type: docs
weight: 118
url: /fa/system.web.services.protocols/details_soapexception/ismustunderstandfaultcode/
---
## Details_SoapException::IsMustUnderstandFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) method

Checks if the specified code is equal to the 'MustUnderstand' SOAP fault code.

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsMustUnderstandFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | کد خطای SOAP برای بررسی. |

### مقدار بازگشتی

True وقتی که کد مشخص‌شده برابر با کد خطای SOAP 'MustUnderstand' باشد، در غیر این صورت false.

## مراجعه به

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* کلاس [Details_SoapException](../)
* فضای نام [System::Web::Services::Protocols](../../)
* کتابخانه [Aspose.Slides](../../../)