---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API-referencia
description: Egyetlen csomópontot választ ki az XPathNavigatorban a megadott XPath lekérdezés használatával.
type: docs
weight: 781
url: /hu/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) metódus


Egyetlen csomópontot választ ki a [XPathNavigator](../)-ben a megadott [XPath](../../) lekérdezés használatával.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Egy [String](../../../system/string/), amely egy [XPath](../../) kifejezést képvisel. |

### Visszatérési érték

Egy [XPathNavigator](../) objektum, amely a megadott [XPath](../../) lekérdezéshez tartozó első egyező csomópontot tartalmaz; egyébként **nullptr**, ha nincs lekérdezési eredmény.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) metódus


Egyetlen csomópontot választ ki a [XPathNavigator](../) objektumban a megadott [XPath](../../) lekérdezés használatával, a [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektumot megadva a névtér előtagok feloldásához.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Egy [String](../../../system/string/), amely egy [XPath](../../) kifejezést képvisel. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | A [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) objektum, amely a [XPath](../../) lekérdezésben a névtér előtagok feloldására szolgál. |

### Visszatérési érték

Egy [XPathNavigator](../) objektum, amely a megadott [XPath](../../) lekérdezéshez tartozó első egyező csomópontot tartalmaz; egyébként **nullptr**, ha nincs lekérdezési eredmény.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) metódus


Egyetlen csomópontot választ ki a [XPathNavigator](../)-ban a megadott [XPathExpression](../../xpathexpression/) objektum használatával.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Egy [XPathExpression](../../xpathexpression/) objektum, amely a lefordított [XPath](../../) lekérdezést tartalmaz. |

### Visszatérési érték

Egy [XPathNavigator](../) objektum, amely a megadott [XPath](../../) lekérdezéshez tartozó első egyező csomópontot tartalmaz; egyébként **nullptr**, ha nincs lekérdezési eredmény.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)