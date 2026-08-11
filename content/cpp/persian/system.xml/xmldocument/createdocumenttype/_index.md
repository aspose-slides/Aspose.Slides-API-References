---
title: CreateDocumentType()
second_title: Aspose.Slides برای مرجع API C++
description: یک شیء جدید XmlDocumentType را برمی‌گرداند.
type: docs
weight: 313
url: /fa/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method

یک شیء جدید [XmlDocumentType](../../xmldocumenttype/) را باز می‌گرداند.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام نوع سند. |
| publicId | const [String](../../../system/string/)\& | شناسه عمومی نوع سند یا **nullptr**. می‌توانید یک URI عمومی و همچنین یک شناسه سیستم برای شناسایی مکان زیرمجموعه DTD خارجی مشخص کنید. |
| systemId | const [String](../../../system/string/)\& | شناسه سیستم نوع سند یا **nullptr**. URL مکان فایل برای زیرمجموعه DTD خارجی را مشخص می‌کند. |
| internalSubset | const [String](../../../system/string/)\& | زیرمجموعه داخلی DTD نوع سند یا **nullptr**. |

### مقدار بازگشت

[XmlDocumentType](../../xmldocumenttype/) جدید.

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [XmlDocumentType](../../xmldocumenttype/)
* کلاس [String](../../../system/string/)
* کلاس [XmlDocument](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)