---
title: SetContext()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, especifica o objeto XmlNamespaceManager a ser usado para a resolução de namespaces.
type: docs
weight: 53
url: /pt/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) método

Quando sobrescrito em uma classe derivada, especifica o objeto [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) a ser usado para a resolução de namespaces.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Um objeto [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) a ser usado para a resolução de namespaces. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) método

Quando sobrescrito em uma classe derivada, especifica o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) a ser usado para a resolução de namespaces.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Um objeto que implementa a interface [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) a ser usado para a resolução de namespaces. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Classe [XPathExpression](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espaço de nomes [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)