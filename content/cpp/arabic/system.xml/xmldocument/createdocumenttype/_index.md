---
title: CreateDocumentType()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إرجاع كائن XmlDocumentType جديد.
type: docs
weight: 313
url: /ar/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String\&, const String\&, const String\&, const String\&) method


إرجاع كائن [XmlDocumentType](../../xmldocumenttype/) جديد.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


### المعاملات

| المُعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم نوع المستند. |
| publicId | const [String](../../../system/string/)\& | المعرّف العام لنوع المستند أو **nullptr**. يمكنك تحديد URI عام وأيضًا معرف نظام لتحديد موقع مجموعة DTD الخارجية. |
| systemId | const [String](../../../system/string/)\& | المعرّف النظامي لنوع المستند أو **nullptr**. يحدد عنوان URL لموقع الملف لمجموعة DTD الخارجية. |
| internalSubset | const [String](../../../system/string/)\& | المجموعة الداخلية لـ DTD لنوع المستند أو **nullptr**. |

### قيمة الإرجاع

الـ [XmlDocumentType](../../xmldocumenttype/) الجديد.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlDocumentType](../../xmldocumenttype/)
* الفئة [String](../../../system/string/)
* الفئة [XmlDocument](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)