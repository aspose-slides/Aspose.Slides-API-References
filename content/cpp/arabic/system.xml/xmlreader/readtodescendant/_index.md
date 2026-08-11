---
title: ReadToDescendant()
second_title: Aspose.Slides للغة C++ مرجع API
description: يقوم بنقل XmlReader إلى العنصر اللاحق التالي بالاسم المؤهل المحدد.
type: docs
weight: 911
url: /ar/system.xml/xmlreader/readtodescendant/
---
## XmlReader::ReadToDescendant(String) طريقة

ينقل [XmlReader](../) إلى العنصر اللاحق التالي بالاسم المؤهل المحدد.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للعنصر الذي ترغب في الانتقال إليه. |

### قيمة الإرجاع

**true** إذا تم العثور على عنصر لاحق مطابق؛ وإلا **false**. إذا لم يتم العثور على عنصر فرعي مطابق، يتم وضع [XmlReader](../) على علامة الإغلاق (القيمة [XmlReader::get_NodeType](../get_nodetype/) هي [XmlNodeType::EndElement](../../xmlnodetype/)) للعنصر. إذا لم يكن [XmlReader](../) موضعًا على عنصر عند استدعاء [XmlReader::ReadToDescendant(String)](./)، فإن هذه الطريقة تُرجع **false** ولا يتغير موضع [XmlReader](../).

## XmlReader::ReadToDescendant(String, String) طريقة

ينقل [XmlReader](../) إلى العنصر اللاحق التالي بالاسم المحلي المحدد ومُعرف مساحة الاسم.

```cpp
virtual bool System::Xml::XmlReader::ReadToDescendant(String localName, String namespaceURI)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للعنصر الذي ترغب في الانتقال إليه. |
| namespaceURI | [String](../../../system/string/) | معرف مساحة الاسم للعنصر الذي ترغب في الانتقال إليه. |

### قيمة الإرجاع

**true** إذا تم العثور على عنصر لاحق مطابق؛ وإلا **false**. إذا لم يتم العثور على عنصر فرعي مطابق، يتم وضع [XmlReader](../) على علامة الإغلاق (القيمة [XmlReader::get_NodeType](../get_nodetype/) هي [XmlNodeType::EndElement](../../xmlnodetype/)) للعنصر. إذا لم يكن [XmlReader](../) موضعًا على عنصر عند استدعاء [XmlReader::ReadToDescendant(String,String)](./)، فإن هذه الطريقة تُرجع **false** ولا يتغير موضع [XmlReader](../).

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* مساحة الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)