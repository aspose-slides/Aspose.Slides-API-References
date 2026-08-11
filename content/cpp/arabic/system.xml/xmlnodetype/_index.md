---
title: XmlNodeType
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد نوع العقدة.
type: docs
weight: 833
url: /ar/system.xml/xmlnodetype/
---
## XmlNodeType enum

Specifies the type of node.

```cpp
enum class XmlNodeType
```

### Values

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| None | 0 | يتم إرجاع هذا بواسطة [XmlReader](../xmlreader/) إذا لم يتم استدعاء طريقة **Read**. |
| Element | 1 | عنصر (على سبيل المثال، **<item>**). |
| Attribute | 2 | سمة (على سبيل المثال، **id='123'**). |
| Text | 3 | محتوى النص لعقدة. لا يمكن لعقدة [XmlNodeType::Text](./) أن تحتوي على عقد فرعية. يمكن أن تظهر كعقدة فرعية لعقد [XmlNodeType::Attribute](./)، [XmlNodeType::DocumentFragment](./)، [XmlNodeType::Element](./)، و[XmlNodeType::EntityReference](./). |
| CDATA | 4 | قسم CDATA (على سبيل المثال، **my escaped text**). |
| EntityReference | 5 | إشارة إلى كيان (على سبيل المثال، **&num;**). |
| Entity | 6 | تصريح كيان (على سبيل المثال، **<!ENTITY...>**). |
| ProcessingInstruction | 7 | تعليمة معالجة (على سبيل المثال، **<?pi test?>**). |
| Comment | 8 | تعليق (على سبيل المثال، ****). |
| Document | 9 | كائن مستند، كجذر شجرة المستند، يوفر إمكانية الوصول إلى مستند XML كامل. |
| DocumentType | 10 | تصريح نوع المستند، المشار إليه بالوسم التالي (على سبيل المثال، **<!DOCTYPE...>**). |
| DocumentFragment | 11 | جزء من المستند. |
| Notation | 12 | ترميز في تصريح نوع المستند (على سبيل المثال، **<!NOTATION...>**). |
| Whitespace | 13 | مسافة بيضاء بين العلامات. |
| SignificantWhitespace | 14 | مسافة بيضاء بين العلامات في نموذج محتوى مختلط أو مسافة بيضاء داخل نطاق **xml:space=\"preserve\"**. |
| EndElement | 15 | وسم عنصر نهائي (على سبيل المثال، ****). |
| EndEntity | 16 | يتم إرجاعه عندما يصل [XmlReader](../xmlreader/) إلى نهاية استبدال الكيان نتيجة لاستدعاء [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | إعلان XML (على سبيل المثال، **<?xml version='1.0'?>**). يجب أن تكون عقدة [XmlNodeType::XmlDeclaration](./) هي أول عقدة في المستند. لا يمكن أن تحتوي على عقد فرعية. هي عقدة فرعية لعقدة [XmlNodeType::Document](./). يمكن أن تحتوي على خصائص توفر معلومات الإصدار والترميز. |

## انظر أيضًا

* النطاق [System::Xml](../)
* المكتبة [Aspose.Slides](../../)