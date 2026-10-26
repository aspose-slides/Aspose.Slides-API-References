---
title: SetContext()
second_title: Riferimento API Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, specifica l'oggetto XmlNamespaceManager da utilizzare per la risoluzione dei namespace.
type: docs
weight: 53
url: /it/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) metodo

Quando sovrascritto in una classe derivata, specifica l'oggetto [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) da utilizzare per la risoluzione dei namespace.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Un oggetto [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) da utilizzare per la risoluzione dei namespace. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) metodo

Quando sovrascritto in una classe derivata, specifica l'oggetto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) da utilizzare per la risoluzione dei namespace.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Un oggetto che implementa l'interfaccia [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) da utilizzare per la risoluzione dei namespace. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Classe [XPathExpression](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)