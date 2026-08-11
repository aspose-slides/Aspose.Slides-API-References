---
title: ReadElementContentAs()
second_title: Aspose.Slides برای C++ مرجع API
description: محتویات عنصر را به‌عنوان نوع درخواست‌شده می‌خواند.
type: docs
weight: 586
url: /fa/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) متد

محتوای عنصر را به‌عنوان نوع درخواست‌شده می‌خواند.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوع مقدار برای بازگرداندن. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | یک شیء [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) که برای حل کردن هر پیشوند فضای نام مرتبط با تبدیل نوع استفاده می‌شود. |

### مقدار بازگشتی

محتوای عنصر تبدیل‌شده به شیء نوع درخواست‌شده.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) متد

تایید می‌کند که نام محلی و URI فضای نام مشخص‌شده با عنصر فعلی مطابقت داشته باشد، سپس محتویات عنصر را به‌عنوان نوع درخواست‌شده می‌خواند.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | نوع مقدار برای بازگرداندن. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | یک شیء [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) که برای حل کردن هر پیشوند فضای نام مرتبط با تبدیل نوع استفاده می‌شود. |
| localName | [String](../../../system/string/) | نام محلی عنصر. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام عنصر. |

### مقدار بازگشتی

محتوای عنصر تبدیل‌شده به شیء نوع درخواست‌شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* کلاس [XmlReader](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)