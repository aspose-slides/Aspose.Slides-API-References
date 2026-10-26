---
title: SetContext()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Gdy zostanie przesłonięta w klasie pochodnej, określa obiekt XmlNamespaceManager używany do rozwiązywania przestrzeni nazw.
type: docs
weight: 53
url: /pl/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) metoda


Gdy jest przesłonięta w klasie pochodnej, określa obiekt [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) używany do rozwiązywania przestrzeni nazw.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | Obiekt [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) używany do rozwiązywania przestrzeni nazw. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) metoda


Gdy jest przesłonięta w klasie pochodnej, określa obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania przestrzeni nazw.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt implementujący interfejs [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania przestrzeni nazw. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Klasa [XPathExpression](../)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)