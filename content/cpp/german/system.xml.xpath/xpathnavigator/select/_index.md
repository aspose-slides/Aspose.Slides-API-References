---
title: Select()
second_title: Aspose.Slides für C++ API-Referenz
description: Wählt einen Knotensatz aus, indem der angegebene XPath-Ausdruck verwendet wird.
type: docs
weight: 794
url: /de/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) Methode

Wählt einen Knotensatz aus, indem der angegebene [XPath](../../)-Ausdruck verwendet wird.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ein [String](../../../system/string/) der einen [XPath](../../)-Ausdruck darstellt. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/), der auf den ausgewählten Knotensatz zeigt.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) Methode

Wählt einen Knotensatz aus, indem der angegebene [XPath](../../)-Ausdruck zusammen mit dem angegebenen [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt verwendet wird, um Namensraum-Präfixe aufzulösen.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Ein [String](../../../system/string/) der einen [XPath](../../)-Ausdruck darstellt. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)-Objekt, das zum Auflösen von Namensraum-Präfixen verwendet wird. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/), der auf den ausgewählten Knotensatz zeigt.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) Methode

Wählt einen Knotensatz aus, indem das angegebene [XPathExpression](../../xpathexpression/) verwendet wird.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ein [XPathExpression](../../xpathexpression/)-Objekt, das die kompilierte [XPath](../../)-Abfrage enthält. |

### Rückgabewert

Ein [XPathNodeIterator](../../xpathnodeiterator/), der auf den ausgewählten Knotensatz zeigt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNodeIterator](../../xpathnodeiterator/)
* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XPathExpression](../../xpathexpression/)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)