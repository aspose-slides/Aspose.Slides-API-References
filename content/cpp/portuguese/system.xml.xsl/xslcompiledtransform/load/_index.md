---
title: Load()
second_title: Referência da API Aspose.Slides for C++
description: Compila a folha de estilo contida no XmlReader.
type: docs
weight: 27
url: /pt/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) método

Compila a folha de estilo contida em [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Um [XmlReader](../../../system.xml/xmlreader/) contendo a folha de estilo. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) método

Compila a folha de estilo XSLT contida em [XmlReader](../../../system.xml/xmlreader/). O [XmlResolver](../../../system.xml/xmlresolver/) resolve quaisquer elementos **import** ou **include** de XSLT e as configurações de XSLT determinam as permissões para a folha de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | O [XmlReader](../../../system.xml/xmlreader/) contendo a folha de estilo. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | O [XsltSettings](../../xsltsettings/) a ser aplicado à folha de estilo. Se isso for **nullptr**, a configuração [XsltSettings::get_Default](../../xsltsettings/get_default/) é aplicada. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver quaisquer folhas de estilo referenciadas em elementos **import** e **include** de XSLT. Se isso for **nullptr**, recursos externos não são resolvidos. |

## XslCompiledTransform::Load(const String\&) método

Carrega e compila a folha de estilo localizada no URI especificado.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | O URI da folha de estilo. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) método

Carrega e compila a folha de estilo XSLT especificada pelo URI. O [XmlResolver](../../../system.xml/xmlresolver/) resolve quaisquer elementos **import** ou **include** de XSLT e as configurações de XSLT determinam as permissões para a folha de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | O URI da folha de estilo. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | O [XsltSettings](../../xsltsettings/) a ser aplicado à folha de estilo. Se isso for **nullptr**, a configuração [XsltSettings::get_Default](../../xsltsettings/get_default/) é aplicada. |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver o URI da folha de estilo e quaisquer folhas de estilo referenciadas em elementos **import** e **include** de XSLT. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) método

Compila a folha de estilo contida no objeto IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo a folha de estilo. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) método

Compila a folha de estilo XSLT contida no IXPathNavigable. O [XmlResolver](../../../system.xml/xmlresolver/) resolve quaisquer elementos **import** ou **include** de XSLT e as configurações de XSLT determinam as permissões para a folha de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Um objeto que implementa a interface IXPathNavigable. Pode ser um [XmlNode](../../../system.xml/xmlnode/) (tipicamente um [XmlDocument](../../../system.xml/xmldocument/)) ou um XPathDocument contendo a folha de estilo. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | O [XsltSettings](../../xsltsettings/) a ser aplicado à folha de estilo. Se isso for **nullptr**, a configuração [XsltSettings::get_Default](../../xsltsettings/get_default/) é aplicada. |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | O [XmlResolver](../../../system.xml/xmlresolver/) usado para resolver quaisquer folhas de estilo referenciadas em elementos **import** e **include** de XSLT. Se isso for **nullptr**, recursos externos não são resolvidos. |

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XslCompiledTransform](../)
* Classe [XsltSettings](../../xsltsettings/)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Classe [String](../../../system/string/)
* Classe [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Namespace [System::Xml::Xsl](../../)
* Biblioteca [Aspose.Slides](../../../)