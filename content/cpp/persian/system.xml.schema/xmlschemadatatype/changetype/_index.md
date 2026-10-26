---
title: ChangeType()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار مشخص‌شده را که نوع آن یکی از نمایش‌های معتبر نوع طرح‌واره XML است که توسط XmlSchemaDatatype نمایانده می‌شود، به نوع زمان اجرای مشخص‌شده تبدیل می‌کند.
type: docs
weight: 66
url: /fa/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method

مقدار مشخص شده را که نوع آن یکی از نمایه‌های معتبر نوع طرح‌واره XML است که توسط [XmlSchemaDatatype](../) نمایانده شده است، به نوع زمان اجرا مشخص شده تبدیل می‌کند.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | مقدار ورودی برای تبدیل به نوع مشخص شده. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | نوع هدف برای تبدیل مقدار ورودی به آن. |

### مقدار بازگشتی

مقدار ورودی تبدیل‌شده.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

مقدار مشخص شده را که نوع آن یکی از نمایه‌های معتبر نوع طرح‌واره XML است که توسط [XmlSchemaDatatype](../) نمایانده شده است، به نوع زمان اجرا مشخص شده با استفاده از [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) تبدیل می‌کند، در صورتی که [XmlSchemaDatatype](../) نوع **xs:QName** یا نوع مشتق شده از آن باشد.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | مقدار ورودی برای تبدیل به نوع مشخص شده. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | نوع هدف برای تبدیل مقدار ورودی به آن. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | یک [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) برای حل پیشوندهای فضای نام استفاده می‌شود. این تنها زمانی مفید است که [XmlSchemaDatatype](../) نوع **xs:QName** یا نوع مشتق شده از آن باشد. |

### مقدار بازگشتی

مقدار ورودی تبدیل‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [XmlSchemaDatatype](../)
* کلاس [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* فضای‌نام [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)