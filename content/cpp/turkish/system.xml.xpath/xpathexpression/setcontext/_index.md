---
title: SetContext()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, namespace çözümlemesi için kullanılacak XmlNamespaceManager nesnesini belirtir.
type: docs
weight: 53
url: /tr/system.xml.xpath/xpathexpression/setcontext/
---
## XPathExpression::SetContext(SharedPtr\<XmlNamespaceManager\>) metodu


Derived sınıfta geçersiz kılındığında, [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) nesnesini namespace çözümlemesi için kullanır.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<XmlNamespaceManager> nsManager)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| nsManager | [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)\> | [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/) nesnesi, namespace çözümlemesi için kullanılır. |

## XPathExpression::SetContext(SharedPtr\<IXmlNamespaceResolver\>) metodu


Derived sınıfta geçersiz kılındığında, [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) nesnesini namespace çözümlemesi için kullanır.

```cpp
virtual void System::Xml::XPath::XPathExpression::SetContext(SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Namespace çözümlemesi için kullanılacak [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) arayüzünü uygulayan bir nesne. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlNamespaceManager](../../../system.xml/xmlnamespacemanager/)
* Sınıf [XPathExpression](../)
* Sınıf [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* AdAlanı [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)