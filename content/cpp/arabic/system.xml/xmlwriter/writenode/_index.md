---
title: WriteNode()
second_title: Aspose.Slides للغة C++ مرجع API
description: عند تجاوزها في فئة مشتقة، تقوم بنسخ كل شيء من القارئ إلى الكاتب وتُحَرِّك القارئ إلى بداية الأخ الأصغر التالي.
type: docs
weight: 430
url: /ar/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) طريقة

عند تجاوزها في فئة مشتقة، تقوم بنسخ كل شيء من القارئ إلى الكاتب وتُحَرِّك القارئ إلى بداية الأخ الأصغر التالي.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | الـ [XmlReader](../../xmlreader/) للقراءة منه. |
| defattr | **bool** | **true** لنسخ السمات الافتراضية من الـ [XmlReader](../../xmlreader/)؛ وإلا، **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) طريقة

ينسخ كل شيء من كائن XPathNavigator إلى الكاتب. يبقى موضع XPathNavigator دون تغيير.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | الـ XPathNavigator للنسخ منه. |
| defattr | **bool** | **true** لنسخ السمات الافتراضية؛ وإلا، **false**. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* الفئة [XmlReader](../../xmlreader/)
* الفئة [XmlWriter](../)
* الفئة [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* المجال [System::Xml](../../)
* Library [Aspose.Slides](../../../)