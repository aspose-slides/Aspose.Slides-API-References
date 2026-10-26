---
title: Load()
second_title: Referencia de API de Aspose.Slides para C++
description: Compila la hoja de estilo contenida en el XmlReader.
type: docs
weight: 27
url: /es/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) método


Compila la hoja de estilo contenida en el [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Un [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) método


Compila la hoja de estilo XSLT contenida en el [XmlReader](../../../system.xml/xmlreader/). El [XmlResolver](../../../system.xml/xmlresolver/) resuelve cualquier elemento **import** o **include** de XSLT y la configuración de XSLT determina los permisos para la hoja de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | El [XmlReader](../../../system.xml/xmlreader/) que contiene la hoja de estilo. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | El [XsltSettings](../../xsltsettings/) a aplicar a la hoja de estilo. Si es **nullptr**, se aplica la configuración [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver cualquier hoja de estilo referenciada en elementos **import** y **include** de XSLT. Si es **nullptr**, los recursos externos no se resuelven. |

## XslCompiledTransform::Load(const String\&) método


Carga y compila la hoja de estilo ubicada en el URI especificado.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | El URI de la hoja de estilo. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) método


Carga y compila la hoja de estilo XSLT especificada por el URI. El [XmlResolver](../../../system.xml/xmlresolver/) resuelve cualquier elemento **import** o **include** de XSLT y la configuración de XSLT determina los permisos para la hoja de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | El URI de la hoja de estilo. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | El [XsltSettings](../../xsltsettings/) a aplicar a la hoja de estilo. Si es **nullptr**, se aplica la configuración [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver el URI de la hoja de estilo y cualquier hoja de estilo referenciada en elementos **import** y **include** de XSLT. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) método


Compila la hoja de estilo contenida en el objeto IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene la hoja de estilo. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) método


Compila la hoja de estilo XSLT contenida en el IXPathNavigable. El [XmlResolver](../../../system.xml/xmlresolver/) resuelve cualquier elemento **import** o **include** de XSLT y la configuración de XSLT determina los permisos para la hoja de estilo.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Un objeto que implementa la interfaz IXPathNavigable. Puede ser un [XmlNode](../../../system.xml/xmlnode/) (normalmente un [XmlDocument](../../../system.xml/xmldocument/)), o un XPathDocument que contiene la hoja de estilo. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | El [XsltSettings](../../xsltsettings/) a aplicar a la hoja de estilo. Si es **nullptr**, se aplica la configuración [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | El [XmlResolver](../../../system.xml/xmlresolver/) utilizado para resolver cualquier hoja de estilo referenciada en elementos **import** y **include** de XSLT. Si es **nullptr**, los recursos externos no se resuelven. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlReader](../../../system.xml/xmlreader/)
* Clase [XslCompiledTransform](../)
* Clase [XsltSettings](../../xsltsettings/)
* Clase [XmlResolver](../../../system.xml/xmlresolver/)
* Clase [String](../../../system/string/)
* Clase [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Espacio de nombres [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)