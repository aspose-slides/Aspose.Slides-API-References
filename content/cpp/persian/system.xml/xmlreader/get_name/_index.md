---
title: get_Name()
second_title: مرجع API Aspose.Slides برای C++
description: هنگامی که در یک کلاس مشتق‌شده بازنویسی شود، نام کامل گرهٔ جاری را برمی‌گرداند.
type: docs
weight: 27
url: /fa/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() متد


زمانی که در یک کلاس مشتق‌شده بازنویسی شود، نام کامل گرهٔ جاری را برمی‌گرداند.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### مقدار بازگشتی

نام کامل گرهٔ جاری. برای مثال، **Name** برابر **bk:book** برای عنصر **<bk:book>** است.

## نکات

نام بازگردانده شده به مقدار [XmlReader::get_NodeType](../get_nodetype/) گره وابسته است. انواع گره‌های زیر مقادیر ذکر شده را برمی‌گردانند. سایر انواع گره مقدار رشتهٔ خالی را برمی‌گردانند.

| نوع گره | نام |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| نام ویژگی. |
| `DocumentType`| نام نوع سند. |
| `Element`| نام برچسب. |
| `EntityReference`| نام موجودیتی که ارجاع داده شده است. |
| `ProcessingInstruction`| هدف دستور پردازش. |
| [XmlDeclaration](../../xmldeclaration/)| رشتهٔ لفظی `xml`. |


## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [XmlReader](../)
* فضای نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)