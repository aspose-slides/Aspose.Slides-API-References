---
title: ReadContentAs()
second_title: Aspose.Slides برای مرجع API C++
description: محتوا را به عنوان یک شیء از نوع مشخص‌شده می‌خواند.
type: docs
weight: 456
url: /fa/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) متد

محتوا را به عنوان یک شیء از نوع مشخص‌شده می‌خواند.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوع مقدار بازگردانده‌شده. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | یک شیء [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) که برای حل هر پیشوند فضای نام مرتبط با تبدیل نوع استفاده می‌شود. به عنوان مثال، می‌توان از آن هنگام تبدیل شیء [XmlQualifiedName](../../xmlqualifiedname/) به **xs:string** استفاده کرد. این مقدار می‌تواند **nullptr** باشد. |

### مقدار بازگشت

محتوای متنی ترکیبی یا مقدار ویژگی که به نوع درخواست‌شده تبدیل شده است.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)