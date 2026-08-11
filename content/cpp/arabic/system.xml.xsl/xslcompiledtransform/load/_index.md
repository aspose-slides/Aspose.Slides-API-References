---
title: Load()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++ دليل
description: يقوم بتجميع ورقة الأنماط الموجودة في XmlReader.
type: docs
weight: 27
url: /ar/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) طريقة

يقوم بتجميع ورقة الأنماط الموجودة في [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### المعاملات

| المعامل | النّوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | كائن [XmlReader](../../../system.xml/xmlreader/) يحتوي على ورقة الأنماط. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) طريقة

يقوم بتجميع ورقة الأنماط XSLT الموجودة في [XmlReader](../../../system.xml/xmlreader/). يقوم [XmlResolver](../../../system.xml/xmlresolver/) بحل أي عناصر **import** أو **include** في XSLT وتحدد إعدادات XSLT الأذونات لورقة الأنماط.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### المعاملات

| المعامل | النّوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | ال[XmlReader](../../../system.xml/xmlreader/) الذي يحتوي على ورقة الأنماط. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | الإعداد [XsltSettings](../../xsltsettings/) لتطبيقه على ورقة الأنماط. إذا كان هذا **nullptr**، يتم تطبيق إعداد [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | ال[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل أي أوراق أنماط مُشار إليها في عناصر **import** و **include** في XSLT. إذا كان هذا **nullptr**، لا يتم حل الموارد الخارجية. |

## XslCompiledTransform::Load(const String\&) طريقة

يقوم بتحميل وتجميع ورقة الأنماط الموجودة في URI المحدد.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### المعاملات

| المعامل | النّوع | الوصف |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI لورقة الأنماط. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) طريقة

يقوم بتحميل وتجميع ورقة الأنماط XSLT المحددة بالـ URI. يقوم [XmlResolver](../../../system.xml/xmlresolver/) بحل أي عناصر **import** أو **include** في XSLT وتحدد إعدادات XSLT الأذونات لورقة الأنماط.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### المعاملات

| المعامل | النّوع | الوصف |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI لورقة الأنماط. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | الإعداد [XsltSettings](../../xsltsettings/) لتطبيقه على ورقة الأنماط. إذا كان هذا **nullptr**، يتم تطبيق إعداد [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | ال[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل URI ورقة الأنماط وأية أوراق أنماط مُشار إليها في عناصر **import** و **include** في XSLT. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) طريقة

يقوم بتجميع ورقة الأنماط الموجودة داخل كائن IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### المعاملات

| المعامل | النّوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبّق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/))، أو XPathDocument يحتوي على ورقة الأنماط. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) طريقة

يقوم بتجميع ورقة الأنماط XSLT الموجودة داخل IXPathNavigable. يقوم [XmlResolver](../../../system.xml/xmlresolver/) بحل أي عناصر **import** أو **include** في XSLT وتحدد إعدادات XSLT الأذونات لورقة الأنماط.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### المعاملات

| المعامل | النّوع | الوصف |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | كائن يطبّق واجهة IXPathNavigable. يمكن أن يكون إما [XmlNode](../../../system.xml/xmlnode/) (عادةً [XmlDocument](../../../system.xml/xmldocument/))، أو XPathDocument يحتوي على ورقة الأنماط. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | الإعداد [XsltSettings](../../xsltsettings/) لتطبيقه على ورقة الأنماط. إذا كان هذا **nullptr**، يتم تطبيق إعداد [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | ال[XmlResolver](../../../system.xml/xmlresolver/) المستخدم لحل أي أوراق أنماط مُشار إليها في عناصر **import** و **include** في XSLT. إذا كان هذا **nullptr**، لا يتم حل الموارد الخارجية. |

## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslCompiledTransform](../)
* Class [XsltSettings](../../xsltsettings/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [String](../../../system/string/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)