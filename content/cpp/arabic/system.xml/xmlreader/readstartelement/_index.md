---
title: ReadStartElement()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يتحقق من أن العقدة الحالية عنصر ويُحَرِّك القارئ إلى العقدة التالية.
type: docs
weight: 846
url: /ar/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() طريقة

يتحقق من أن العقدة الحالية عنصر ويُحَرِّك القارئ إلى العقدة التالية.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) طريقة

يتحقق من أن عقدة المحتوى الحالية عنصر مع القيمة [XmlReader::get_Name](../get_name/) المحددة ويُحَرِّك القارئ إلى العقدة التالية.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| name | [String](../../../system/string/) | الاسم المؤهل للعنصر. |

## XmlReader::ReadStartElement(String, String) طريقة

يتحقق من أن عقدة المحتوى الحالية عنصر مع القيمتين [XmlReader::get_LocalName](../get_localname/) و [XmlReader::get_NamespaceURI](../get_namespaceuri/) المحددتين ويُحَرِّك القارئ إلى العقدة التالية.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### المعلمات

| معامل | نوع | الوصف |
| --- | --- | --- |
| localname | [String](../../../system/string/) | الاسم المحلي للعنصر. |
| ns | [String](../../../system/string/) | معرف الـ URI للمساحة الاسمية للعنصر. |

## أنظر أيضًا

* فئة [XmlReader](../)
* فئة [String](../../../system/string/)
* مساحة اسم [System::Xml](../../)
* مكتبة [Aspose.Slides](../../../)