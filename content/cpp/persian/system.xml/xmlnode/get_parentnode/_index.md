---
title: get_ParentNode()
second_title: Aspose.Slides برای C++ مرجع API
description: والد این گره را برمی‌گرداند (برای گره‌هایی که می‌توانند والد داشته باشند).
type: docs
weight: 53
url: /fa/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() متد

والد این گره را برمی‌گرداند (برای گره‌هایی که می‌توانند والد داشته باشند).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### مقدار بازگشت

[XmlNode](../) که والد گره فعلی است.

## نکات

اگر یک گره تازه ایجاد شده باشد و هنوز به درخت اضافه نشده باشد، یا اگر از درخت حذف شده باشد، والد **nullptr** است. برای تمام گره‌های دیگر، مقدار بازگشتی بستگی به [XmlNode::get_NodeType](../get_nodetype/) گره دارد. جدول زیر مقادیر بازگشتی ممکن برای متد **get_NodeType** را توصیف می‌کند.

| NodeType | مقدار بازگشت ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | `nullptr` را برمی‌گرداند؛ این گره‌ها والد ندارند. |
| CDATA | عنصر یا مرجع موجودیتی که شامل بخش CDATA است را برمی‌گرداند. |
| Comment | عنصر، مرجع موجودیت، نوع سند، یا سند حاوی نظر را برمی‌گرداند. |
| DocumentType | گره سند را برمی‌گرداند. |
| Element | گره والد عنصر را برمی‌گرداند. اگر عنصر ریشه در درخت باشد، والد گره سند است. |
| EntityReference | عنصر، ویژگی، یا مرجع موجودیتی که شامل مرجع موجودیت است را برمی‌گرداند. |
| ProcessingInstruction | سند، عنصر، نوع سند، یا مرجع موجودیتی که شامل دستور پردازش است را برمی‌گرداند. |
| [Text](../../../system.text/) | عنصر والد، ویژگی، یا مرجع موجودیتی که شامل گره متن است را برمی‌گرداند. |

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlNode](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)