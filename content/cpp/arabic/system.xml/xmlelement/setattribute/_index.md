---
title: SetAttribute()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط قيمة السمة بالاسم المحدد.
type: docs
weight: 222
url: /ar/system.xml/xmlelement/setattribute/
---
## XmlElement::SetAttribute(String, String) طريقة

يضبط قيمة السمة بالاسم المحدد.

```cpp
virtual void System::Xml::XmlElement::SetAttribute(String name, String value)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم السمة لإنشائها أو تعديلها. هذا اسم مؤهل. إذا كان الاسم يحتوي على نقطتين فإنَّه يُقسم إلى مكوّنات البادئة والاسم المحلي. |
| value | [String](../../../system/string/) | القيمة التي سيتم تعيينها للسمة. |

## XmlElement::SetAttribute(String, String, String) طريقة

يضبط قيمة السمة بالاسم المحلي المحدد وURI مساحة الاسم.

```cpp
virtual String System::Xml::XmlElement::SetAttribute(String localName, String namespaceURI, String value)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للسمة. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للسمة. |
| value | [String](../../../system/string/) | القيمة التي سيتم تعيينها للسمة. |

### قيمة الإرجاع

قيمة السمة.

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlElement](../)
* مساحة الاسم [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)