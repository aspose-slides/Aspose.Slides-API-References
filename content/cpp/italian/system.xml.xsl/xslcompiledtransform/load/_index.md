---
title: Load()
second_title: Riferimento API di Aspose.Slides per C++
description: Compila il foglio di stile contenuto nel XmlReader.
type: docs
weight: 27
url: /it/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) metodo


Compila il foglio di stile contenuto nel [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) contenente il foglio di stile. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metodo


Compila il foglio di stile XSLT contenuto nel [XmlReader](../../../system.xml/xmlreader/). Il [XmlResolver](../../../system.xml/xmlresolver/) risolve eventuali elementi **import** o **include** XSLT e le impostazioni XSLT determinano le autorizzazioni per il foglio di stile.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Il [XmlReader](../../../system.xml/xmlreader/) contenente il foglio di stile. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Le [XsltSettings](../../xsltsettings/) da applicare al foglio di stile. Se è **nullptr**, viene applicata l’impostazione [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per risolvere i fogli di stile referenziati negli elementi XSLT **import** e **include**. Se è **nullptr**, le risorse esterne non vengono risolte. |

## XslCompiledTransform::Load(const String\&) metodo


Carica e compila il foglio di stile situato all’URI specificato.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | L’URI del foglio di stile. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) metodo


Carica e compila il foglio di stile XSLT specificato dall’URI. Il [XmlResolver](../../../system.xml/xmlresolver/) risolve eventuali elementi **import** o **include** XSLT e le impostazioni XSLT determinano le autorizzazioni per il foglio di stile.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | L’URI del foglio di stile. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | Le [XsltSettings](../../xsltsettings/) da applicare al foglio di stile. Se è **nullptr**, viene applicata l’impostazione [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per risolvere l’URI del foglio di stile e i fogli di stile referenziati negli elementi XSLT **import** e **include**. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metodo


Compila il foglio di stile contenuto nell’oggetto IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l’interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument contenente il foglio di stile. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) metodo


Compila il foglio di stile XSLT contenuto nell’IXPathNavigable. Il [XmlResolver](../../../system.xml/xmlresolver/) risolve eventuali elementi **import** o **include** XSLT e le impostazioni XSLT determinano le autorizzazioni per il foglio di stile.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l’interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)) o un XPathDocument contenente il foglio di stile. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | Le [XsltSettings](../../xsltsettings/) da applicare al foglio di stile. Se è **nullptr**, viene applicata l’impostazione [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per risolvere eventuali fogli di stile referenziati negli elementi XSLT **import** e **include**. Se è **nullptr**, le risorse esterne non vengono risolte. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XslCompiledTransform](../)
* Classe [XsltSettings](../../xsltsettings/)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Classe [String](../../../system/string/)
* Classe [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Spazio dei nomi [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)