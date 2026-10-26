---
title: IsStartElement()
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ C++
description: "يقوم باستدعاء XmlReader::MoveToContent ويختبر إذا كانت عقدة المحتوى الحالية علامة بداية أو علامة عنصر فارغ."
type: docs
weight: 885
url: /ar/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() طريقة

Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### قيمة الإرجاع

**true** إذا وجدت [XmlReader::MoveToContent](../movetocontent/) علامة بداية أو علامة عنصر فارغ؛ **false** إذا تم العثور على نوع عقدة غير [XmlNodeType::Element](../../xmlnodetype/).

## XmlReader::IsStartElement(String) طريقة

Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_Name](../get_name/) value of the element found matches the given argument.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | السلسلة المتطابقة مع قيمة **Name** للعنصر الذي تم العثور عليه. |

### قيمة الإرجاع

**true** إذا كانت العقدة الناتجة عنصرًا وكانت قيمة **Name** تتطابق مع السلسلة المحددة. **false** إذا تم العثور على نوع عقدة غير [XmlNodeType::Element](../../xmlnodetype/) أو إذا لم تتطابق قيمة **Name** للعنصر مع السلسلة المحددة.

## XmlReader::IsStartElement(String, String) طريقة

Calls [XmlReader::MoveToContent](../movetocontent/) and tests if the current content node is a start tag or empty element tag and if the [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values of the element found match the given strings.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localname | [String](../../../system/string/) | السلسلة المتطابقة مع قيمة **LocalName** للعنصر الذي تم العثور عليه. |
| ns | [String](../../../system/string/) | السلسلة المتطابقة مع قيمة **NamespaceURI** للعنصر الذي تم العثور عليه. |

### قيمة الإرجاع

**true** إذا كانت العقدة الناتجة عنصرًا. **false** إذا تم العثور على نوع عقدة غير [XmlNodeType::Element](../../xmlnodetype/) أو إذا لم تتطابق قيمتي **LocalName** و **NamespaceURI** للعنصر مع السلاسل المحددة.

## انظر أيضًا

* فئة [XmlReader](../)
* فئة [String](../../../system/string/)
* نطاق الاسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)