---
title: Load()
second_title: Aspose.Slides per C++ Riferimento API
description: Carica il foglio di stile XSLT contenuto nel XmlReader.
type: docs
weight: 27
url: /it/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) metodo


Carica il foglio di stile XSLT contenuto nel [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un oggetto [XmlReader](../../../system.xml/xmlreader/) che contiene il foglio di stile XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Carica il foglio di stile XSLT contenuto nel [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un oggetto [XmlReader](../../../system.xml/xmlreader/) che contiene il foglio di stile XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per caricare tutti i fogli di stile referenziati negli elementi **xsl:import** e **xsl:include**. Se questo è **nullptr**, le risorse esterne non vengono risolte. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) metodo


Carica il foglio di stile XSLT contenuto nell'IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)), oppure un XPathDocument contenente il foglio di stile XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Carica il foglio di stile XSLT contenuto nell'IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un oggetto che implementa l'interfaccia IXPathNavigable. Può essere un [XmlNode](../../../system.xml/xmlnode/) (tipicamente un [XmlDocument](../../../system.xml/xmldocument/)), oppure un XPathDocument contenente il foglio di stile XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per caricare tutti i fogli di stile referenziati negli elementi **xsl:import** e **xsl:include**. Se questo è **nullptr**, le risorse esterne non vengono risolte. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) metodo


Carica il foglio di stile XSLT contenuto nel XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un oggetto XPathNavigator che contiene il foglio di stile XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Carica il foglio di stile XSLT contenuto nel XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Un oggetto XPathNavigator che contiene il foglio di stile XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) usato per caricare tutti i fogli di stile referenziati negli elementi **xsl:import** e **xsl:include**. Se questo è **nullptr**, le risorse esterne non vengono risolte. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## XslTransform::Load(const String\&) metodo


Carica il foglio di stile XSLT specificato da un URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL che specifica il foglio di stile XSLT da caricare. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metodo


Carica il foglio di stile XSLT specificato da un URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | L'URL che specifica il foglio di stile XSLT da caricare. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Il [XmlResolver](../../../system.xml/xmlresolver/) da usare per caricare il foglio di stile e qualsiasi foglio di stile referenziato negli elementi **xsl:import** e **xsl:include**. Se questo è **nullptr**, viene usato un [XmlUrlResolver](../../../system.xml/xmlurlresolver/) predefinito senza credenziali utente per aprire il foglio di stile. Il [XmlUrlResolver](../../../system.xml/xmlurlresolver/) predefinito non viene utilizzato per risolvere alcuna risorsa esterna nel foglio di stile, quindi gli elementi **xsl:import** e **xsl:include** non vengono risolti. Il [XmlResolver](../../../system.xml/xmlresolver/) non viene memorizzato nella cache dopo il completamento di questo metodo. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XslTransform](../)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Class [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Class [String](../../../system/string/)
* Namespace [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)