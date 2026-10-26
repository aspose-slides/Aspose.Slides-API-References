---
title: IsClientFaultCode()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا کد مشخص شده برابر با کد خطای SOAP 'Client' است.
type: docs
weight: 105
url: /fa/system.web.services.protocols/details_soapexception/isclientfaultcode/
---
## جزئیات_SoapException::IsClientFaultCode(System::SharedPtr\<Xml::XmlQualifiedName\>) متد

بررسی می‌کند که آیا کد مشخص شده برابر با کد خطای SOAP 'Client' است.

```cpp
static bool System::Web::Services::Protocols::Details_SoapException::IsClientFaultCode(System::SharedPtr<Xml::XmlQualifiedName> code)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| code | [System::SharedPtr](../../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\> | کد خطای SOAP برای بررسی. |

## مقدار بازگشت

در صورتی که کد مشخص شده برابر با کد خطای SOAP 'Client' باشد، مقدار True و در غیر این صورت False برگردانده می‌شود.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* کلاس [Details_SoapException](../)
* فضای‌نام [System::Web::Services::Protocols](../../)
* کتابخانه [Aspose.Slides](../../../)