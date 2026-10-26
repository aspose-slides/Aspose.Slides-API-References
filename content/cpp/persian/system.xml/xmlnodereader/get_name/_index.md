---
title: get_Name()
second_title: مرجع API Aspose.Slides برای C++
description: نام معتبر گرهٔ جاری را برمی‌گرداند.
type: docs
weight: 14
url: /fa/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() متد

نام معتبر گرهٔ جاری را برمی‌گرداند.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### مقدار بازگشت

نام معتبر گرهٔ جاری. به عنوان مثال، **Name** برای عنصر **<bk:book>** برابر با **bk:book** است.

## توضیحات

نام بازگردانده شده به مقدار [XmlNodeReader::get_NodeType](../get_nodetype/) گره وابسته است. انواع گره‌های زیر مقادیر ذکر شده را برمی‌گردانند. سایر انواع گره یک رشتهٔ خالی برمی‌گردانند. 

| Node Type | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| نام ویژگی. |
| DocumentType| نام نوع سند. |
| Element| نام برچسب. |
| EntityReference| نام موجودیتی که ارجاع داده شده است. |
| ProcessingInstruction| هدف دستور پردازش. |
| [XmlDeclaration](../../xmldeclaration/)| رشتهٔ ثابت `xml`. |


## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [XmlNodeReader](../)
* نام‌فضا [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)