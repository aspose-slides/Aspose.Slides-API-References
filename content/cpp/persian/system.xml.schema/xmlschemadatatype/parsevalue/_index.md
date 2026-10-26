---
title: ParseValue()
second_title: مرجع API Aspose.Slides برای C++
description: هنگامی که در یک کلاس مشتق‌شده بازنویسی می‌شود، رشته مشخص‌شده را در مقابل یک نوع ساده داخلی یا کاربری اعتبارسنجی می‌کند.
type: docs
weight: 53
url: /fa/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) متد

هنگامی که در یک کلاس مشتق‌شده بازنویسی می‌شود، **string** مشخص‌شده را در مقابل یک نوع ساده داخلی یا کاربری اعتبارسنجی می‌کند.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| s | [String](../../../system/string/) | **string** برای اعتبارسنجی در مقابل نوع ساده. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | [XmlNameTable](../../../system.xml/xmlnametable/) برای استفاده در اتم‌سازی هنگام تجزیه **string** در صورتی که این شیء [XmlSchemaDatatype](../) نوع **xs:NCName** را نشان دهد. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) شیء برای استفاده هنگام تجزیه **string** در صورتی که این شیء [XmlSchemaDatatype](../) نوع **xs:QName** را نشان دهد. |

### مقدار بازگشتی

[Object](../../../system/object/)ی که می‌تواند به‌صورت ایمن به نوع بازگردانده‌شده توسط فراخوانی [XmlSchemaDatatype::get_ValueType](../get_valuetype/) تبدیل شود.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [String](../../../system/string/)
* کلاس [XmlNameTable](../../../system.xml/xmlnametable/)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* کلاس [XmlSchemaDatatype](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)