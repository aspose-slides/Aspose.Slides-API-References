---
title: ReadToNextSibling()
second_title: Aspose.Slides برای C++ مرجع API
description: XmlReader را به عنصر خواهر بعدی با نام کامل مشخص شده پیش می‌برد.
type: docs
weight: 924
url: /fa/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) متد

[XmlReader](../) را به عنصر خواهر بعدی با نام کامل مشخص شده پیش می‌برد.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | [String](../../../system/string/) | نام کامل عنصر خواهر که می‌خواهید به آن بروید. |

### مقدار بازگشت

**true** اگر عنصر خواهر مطابق پیدا شود؛ در غیر این صورت **false**. اگر عنصر خواهر مطابق یافت نشود، [XmlReader](../) در برچسب انتهایی (مقدار [XmlReader::get_NodeType](../get_nodetype/) برابر [XmlNodeType::EndElement](../../xmlnodetype/)) عنصر والد قرار می‌گیرد.

## XmlReader::ReadToNextSibling(String, String) متد

[XmlReader](../) را به عنصر خواهر بعدی با نام محلی و URI فضای نام مشخص پیش می‌برد.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| localName | [String](../../../system/string/) | نام محلی عنصر خواهر که می‌خواهید به آن بروید. |
| namespaceURI | [String](../../../system/string/) | URI فضای نام عنصر خواهر که می‌خواهید به آن بروید. |

### مقدار بازگشت

**true** اگر عنصر خواهر مطابق پیدا شود؛ در غیر این صورت **false**. اگر عنصر خواهر مطابق یافت نشود، [XmlReader](../) در برچسب انتهایی (مقدار [XmlReader::get_NodeType](../get_nodetype/) برابر [XmlNodeType::EndElement](../../xmlnodetype/)) عنصر والد قرار می‌گیرد.

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)