---
title: SetContext()
second_title: Referencia de API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, especifica el objeto XmlNamespaceManager que se usará para la resolución de espacios de nombres.
type: docs
weight: 53
url: /es/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) método

Cuando se sobrescribe en una clase derivada, especifica el objeto [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) que se usará para la resolución de espacios de nombres.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Un objeto [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) que se usará para la resolución de espacios de nombres. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) método

Cuando se sobrescribe en una clase derivada, especifica el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) que se usará para la resolución de espacios de nombres.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Un objeto que implementa la interfaz [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) que se usará para la resolución de espacios de nombres. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Clase [XPathExpression](../)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)