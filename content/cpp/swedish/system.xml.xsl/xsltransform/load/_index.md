---
title: Load()
second_title: Aspose.Slides för C++ API-referens
description: Läser in XSLT-stilmallen som finns i XmlReader.
type: docs
weight: 27
url: /sv/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) metod

Läser in XSLT-stilmallen som finns i [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt som innehåller XSLT-stilmallen. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metod

Läser in XSLT-stilmallen som finns i [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Ett [XmlReader](../../../system.xml/xmlreader/)-objekt som innehåller XSLT-stilmallen. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att ladda alla stilmallar som refereras i **xsl:import** och **xsl:include**-element. Om detta är **nullptr**, löses externa resurser inte upp. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metod

Läser in XSLT-stilmallen som finns i IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan antingen vara ett [XmlNode](../../../system.xml/xmlnode/) (vanligtvis ett [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller XSLT-stilmallen. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metod

Läser in XSLT-stilmallen som finns i IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Ett objekt som implementerar IXPathNavigable-gränssnittet. Det kan antingen vara ett [XmlNode](../../../system.xml/xmlnode/) (vanligtvis ett [XmlDocument](../../../system.xml/xmldocument/)) eller ett XPathDocument som innehåller XSLT-stilmallen. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att ladda alla stilmallar som refereras i **xsl:import** och **xsl:include**-element. Om detta är **nullptr**, löses externa resurser inte upp. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) metod

Läser in XSLT-stilmallen som finns i XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ett XPathNavigator-objekt som innehåller XSLT-stilmallen. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metod

Läser in XSLT-stilmallen som finns i XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Ett XPathNavigator-objekt som innehåller XSLT-stilmallen. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att ladda alla stilmallar som refereras i **xsl:import** och **xsl:include**-element. Om detta är **nullptr**, löses externa resurser inte upp. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## XslTransform::Load(const String\&) metod

Läser in XSLT-stilmallen som anges av en URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL-en som anger XSLT-stilmallen som ska läsas in. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metod

Läser in XSLT-stilmallen som anges av en URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL-en som anger XSLT-stilmallen som ska läsas in. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som ska användas för att läsa in stilmallen och alla stilmallar som refereras i **xsl:import** och **xsl:include**-element. Om detta är **nullptr**, används en standard [XmlUrlResolver](../../../system.xml/xmlurlresolver/) utan användaruppgifter för att öppna stilmallen. Standard-[XmlUrlResolver](../../../system.xml/xmlurlresolver/) används inte för att lösa externa resurser i stilmallen, så **xsl:import** och **xsl:include**-element inte löses. Den [XmlResolver](../../../system.xml/xmlresolver/) cachas inte efter att denna metod har slutförts. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Klass [XslTransform](../)
* Klass [XmlResolver](../../../system.xml/xmlresolver/)
* Klass [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Klass [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Klass [String](../../../system/string/)
* Namnrymd [System::Xml::Xsl](../../)
* Bibliotek [Aspose.Slides](../../../)