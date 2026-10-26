---
title: Load()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بتحميل ورقة نمط XSLT الموجودة في XmlReader.
type: docs
weight: 27
url: /ar/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) طريقة

يحمّل ورقة نمط XSLT الموجودة في [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على ورقة نمط XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحمّل ورقة نمط XSLT الموجودة في [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على ورقة نمط XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | ال[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لتحميل أي ورقة نمط يتم الإشارة إليها في عناصر **xsl:import** و **xsl:include**. إذا كان هذا **nullptr**، لن يتم حل الموارد الخارجية. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتاً بعد انتهاء هذه الطريقة. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) طريقة

يحمّل ورقة نمط XSLT الموجودة في IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن ينفّذ واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/))، أو XPathDocument يحتوي على ورقة نمط XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحمّل ورقة نمط XSLT الموجودة في IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن ينفّذ واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/))، أو XPathDocument يحتوي على ورقة نمط XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | ال[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لتحميل أي ورقة نمط يتم الإشارة إليها في عناصر **xsl:import** و **xsl:include**. إذا كان هذا **nullptr**، لن يتم حل الموارد الخارجية. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتاً بعد انتهاء هذه الطريقة. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) طريقة

يحمّل ورقة نمط XSLT الموجودة في XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على ورقة نمط XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحمّل ورقة نمط XSLT الموجودة في XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | كائن XPathNavigator يحتوي على ورقة نمط XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | ال[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لتحميل أي ورقة نمط يتم الإشارة إليها في عناصر **xsl:import** و **xsl:include**. إذا كان هذا **nullptr**، لن يتم حل الموارد الخارجية. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتاً بعد انتهاء هذه الطريقة. |

## XslTransform::Load(const String\&) طريقة

يحمّل ورقة نمط XSLT المحددة عبر URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL الذي يحدد ورقة نمط XSLT التي سيتم تحميلها. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) طريقة

يحمّل ورقة نمط XSLT المحددة عبر URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | عنوان URL الذي يحدد ورقة نمط XSLT التي سيتم تحميلها. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | ال[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لتحميل ورقة النمط وأي ورقة نمط مُشار إليها في عناصر **xsl:import** و **xsl:include**. إذا كان هذا **nullptr**، يتم استخدام [XmlUrlResolver](../../../system.xml/xmlurlresolver/) افتراضي بدون بيانات اعتماد المستخدم لفتح ورقة النمط. الـ[XmlUrlResolver](../../../system.xml/xmlurlresolver/) الافتراضي غير مستخدم لحل أي موارد خارجية في ورقة النمط، لذا لا يتم حل عناصر **xsl:import** و **xsl:include**. الـ[XmlResolver](../../../system.xml/xmlresolver/) غير مخزن مؤقتاً بعد انتهاء هذه الطريقة. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* صف [XmlReader](../../../system.xml/xmlreader/)
* صف [XslTransform](../)
* صف [XmlResolver](../../../system.xml/xmlresolver/)
* صف [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* صف [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* صف [String](../../../system/string/)
* نطاق [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)