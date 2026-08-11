---
title: ReadToNextSibling()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يتقدم XmlReader إلى العنصر الشقيق التالي بالاسم المؤهل المحدد.
type: docs
weight: 924
url: /ar/system.xml/xmlreader/readtonextsibling/
---
## XmlReader::ReadToNextSibling(String) طريقة

يتقدم [XmlReader](../) إلى العنصر الشقيق التالي بالاسم المؤهل المحدد.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String name)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للعنصر الشقيق الذي تريد الانتقال إليه. |

### قيمة الإرجاع

**true** إذا تم العثور على عنصر شقيق مطابق؛ وإلا **false**. إذا لم يتم العثور على عنصر شقيق مطابق، يتم توضع [XmlReader](../) على وسم الإغلاق (القيمة [XmlReader::get_NodeType](../get_nodetype/) هي [XmlNodeType::EndElement](../../xmlnodetype/)) لعنصر الأب.

## XmlReader::ReadToNextSibling(String, String) طريقة

يتقدم [XmlReader](../) إلى العنصر الشقيق التالي بالاسم المحلي المحدد ومسار مساحة الاسم.

```cpp
virtual bool System::Xml::XmlReader::ReadToNextSibling(String localName, String namespaceURI)
```

### الوسائط

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | الاسم المحلي للعنصر الشقيق الذي تريد الانتقال إليه. |
| namespaceURI | [String](../../../system/string/) | مسار مساحة الاسم للعنصر الشقيق الذي تريد الانتقال إليه. |

### قيمة الإرجاع

**true** إذا تم العثور على عنصر شقيق مطابق؛ وإلا **false**. إذا لم يتم العثور على عنصر شقيق مطابق، يتم توضع [XmlReader](../) على وسم الإغلاق (القيمة [XmlReader::get_NodeType](../get_nodetype/) هي [XmlNodeType::EndElement](../../xmlnodetype/)) لعنصر الأب.

## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [XmlReader](../)
* النطاق [System::Xml](../../)
* المكتبة [Aspose.Slides](../../../)