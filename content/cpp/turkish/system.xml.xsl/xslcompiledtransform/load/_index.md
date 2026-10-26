---
title: Load()
second_title: Aspose.Slides for C++ API Referansı
description: XmlReader içinde bulunan stil sayfasını derler.
type: docs
weight: 27
url: /tr/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) method

[XmlReader](../../../system.xml/xmlreader/) içinde bulunan stil sayfasını derler.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Stili sayfasını içeren bir [XmlReader](../../../system.xml/xmlreader/). |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method

[XmlReader](../../../system.xml/xmlreader/) içinde bulunan XSLT stil sayfasını derler. [XmlResolver](../../../system.xml/xmlresolver/) XSLT **import** veya **include** öğelerini çözer ve XSLT ayarları stil sayfasının izinlerini belirler.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Stil sayfasını içeren [XmlReader](../../../system.xml/xmlreader/). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Stil sayfasına uygulanacak [XsltSettings](../../xsltsettings/). Eğer bu **nullptr** ise, [XsltSettings::get_Default](../../xsltsettings/get_default/) ayarı uygulanır. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | XSLT **import** ve **include** öğelerinde başvurulan stil sayfalarını çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, dış kaynaklar çözülemez. |

## XslCompiledTransform::Load(const String\&) method

Belirtilen URI'deki stil sayfasını yükler ve derler.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Stil sayfasının URI'si. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) method

URI ile belirtilen XSLT stil sayfasını yükler ve derler. [XmlResolver](../../../system.xml/xmlresolver/) XSLT **import** veya **include** öğelerini çözer ve XSLT ayarları stil sayfasının izinlerini belirler.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | Stil sayfasının URI'si. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Stil sayfasına uygulanacak [XsltSettings](../../xsltsettings/). Eğer bu **nullptr** ise, [XsltSettings::get_Default](../../xsltsettings/get_default/) ayarı uygulanır. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Stil sayfası URI'sini ve XSLT **import** ve **include** öğelerinde başvurulan stil sayfalarını çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) method

IXPathNavigable nesnesinde bulunan stil sayfasını derler.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da stil sayfasını içeren bir XPathDocument olabilir. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) method

IXPathNavigable içinde bulunan XSLT stil sayfasını derler. [XmlResolver](../../../system.xml/xmlresolver/) XSLT **import** veya **include** öğelerini çözer ve XSLT ayarları stil sayfasının izinlerini belirler.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | IXPathNavigable arayüzünü uygulayan bir nesne. Bu, bir [XmlNode](../../../system.xml/xmlnode/) (genellikle bir [XmlDocument](../../../system.xml/xmldocument/)) ya da stil sayfasını içeren bir XPathDocument olabilir. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | Stil sayfasına uygulanacak [XsltSettings](../../xsltsettings/). Eğer bu **nullptr** ise, [XsltSettings::get_Default](../../xsltsettings/get_default/) ayarı uygulanır. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | XSLT **import** ve **include** öğelerinde başvurulan stil sayfalarını çözmek için kullanılan [XmlResolver](../../../system.xml/xmlresolver/). Bu **nullptr** ise, dış kaynaklar çözülemez. |

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Sınıf [XslCompiledTransform](../)
* Sınıf [XsltSettings](../../xsltsettings/)
* Sınıf [XmlResolver](../../../system.xml/xmlresolver/)
* Sınıf [String](../../../system/string/)
* Sınıf [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Ad alanı [System::Xml::Xsl](../../)
* Kütüphane [Aspose.Slides](../../../)