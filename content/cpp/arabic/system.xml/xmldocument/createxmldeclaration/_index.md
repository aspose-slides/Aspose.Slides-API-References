---
title: CreateXmlDeclaration()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ عقدة XmlDeclaration بالقيم المحددة.
type: docs
weight: 378
url: /ar/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String\&, const String\&, const String\&) طريقة

ينشئ عقدة [XmlDeclaration](../../xmldeclaration/) بالقيم المحددة.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | يجب أن يكون الإصدار \"1.0\". |
| encoding | const [String](../../../system/string/)\& | قيمة خاصية الترميز. هذا هو الترميز المستخدم عند حفظ الـ [XmlDocument](../) إلى ملف أو تدفق؛ لذلك يجب تعيينه إلى سلسلة يدعمها الصنف [Text::Encoding](../../../system.text/encoding/)، وإلا فستفشل \"XmlDocument::Save(String)\". إذا كان هذا **nullptr** أو [String::Empty](../../../system/string/empty/)، فإن طريقة [XmlDocument::Save](../save/) لا تكتب خاصية الترميز في إعلان XML وبالتالي يُستخدم الترميز الافتراضي UTF-8. |
| standalone | const [String](../../../system/string/)\& | يجب أن تكون القيمة إما \"yes\" أو \"no\". إذا كان هذا **nullptr** أو [String::Empty](../../../system/string/empty/)، فإن طريقة [XmlDocument::Save](../save/) لا تكتب خاصية standalone في إعلان XML. |

### قيمة الإرجاع

العقدة [XmlDeclaration](../../xmldeclaration/) الجديدة.

## ملاحظات

ملاحظة: إذا تم حفظ الـ [XmlDocument](../) إلى إما TextWriter أو [XmlTextWriter](../../xmltextwriter/)، فإن قيمة الترميز هذه تُهمل. بدلاً من ذلك، يُستخدم ترميز الـ TextWriter أو [XmlTextWriter](../../xmltextwriter/). يضمن ذلك أن XML المكتوب يمكن قراءته مرة أخرى باستخدام الترميز الصحيح. 

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* صف [XmlDeclaration](../../xmldeclaration/)
* صف [String](../../../system/string/)
* صف [XmlDocument](../)
* نطاق [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)