---
title: RemoveAttribute()
second_title: Aspose.Slides لـ C++ مرجع API
description: يزيل سمةً بالاسم.
type: docs
weight: 235
url: /ar/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) طريقة

يزيل سمةً بالاسم.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | اسم السمة التي سيتم إزالتها. هذا اسم مؤهل. يتم مقارنته بقيمة **get_Name** للعقدة المطابقة. |

## XmlElement::RemoveAttribute(String, String) طريقة

يزيل سمةً بالاسم المحلي المحدد و URI مساحة الاسم. (إذا كان لل سمة التي أزيلت قيمة افتراضية، يتم استبدالها فوراً).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للسمة التي سيتم إزالتها. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للسمة التي سيتم إزالتها. |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlElement](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)