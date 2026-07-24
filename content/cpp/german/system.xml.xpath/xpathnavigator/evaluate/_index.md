---
title: Evaluate()
second_title: Aspose.Slides für C++ API-Referenz
description: Wertet den angegebenen XPath-Ausdruck aus und gibt das typisierte Ergebnis zurück.
type: docs
weight: 807
url: /de/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) Methode

Wertet den angegebenen [XPath](../../) Ausdruck aus und gibt das typisierte Ergebnis zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Eine Zeichenkette, die einen [XPath](../../) Ausdruck darstellt, der ausgewertet werden kann. |

### Rückgabewert

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), number, string oder node set). Dies entspricht den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) bzw. [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) Methode

Wertet den angegebenen [XPath](../../) Ausdruck aus und gibt das typisierte Ergebnis zurück, wobei das angegebene [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) Objekt verwendet wird, um Namensraumpräfixe im [XPath](../../) Ausdruck aufzulösen.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Eine Zeichenkette, die einen [XPath](../../) Ausdruck darstellt, der ausgewertet werden kann. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Das [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) Objekt, das verwendet wird, um Namensraumpräfixe im [XPath](../../) Ausdruck aufzulösen. |

### Rückgabewert

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), number, string oder node set). Dies entspricht den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) bzw. [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) Methode

Wertet die [XPathExpression](../../xpathexpression/) aus und gibt das typisierte Ergebnis zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ein [XPathExpression](../../xpathexpression/), der ausgewertet werden kann. |

### Rückgabewert

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), number, string oder node set). Dies entspricht den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) bzw. [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) Methode

Verwendet den bereitgestellten Kontext, um die [XPathExpression](../../xpathexpression/) auszuwerten, und gibt das typisierte Ergebnis zurück.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Ein [XPathExpression](../../xpathexpression/), der ausgewertet werden kann. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Ein [XPathNodeIterator](../../xpathnodeiterator/), das auf die ausgewählte Knotengruppe verweist, auf der die Auswertung durchgeführt werden soll. |

### Rückgabewert

Das Ergebnis des Ausdrucks ([Boolean](../../../system/boolean/), number, string oder node set). Dies entspricht den Objekten [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) bzw. [XPathNodeIterator](../../xpathnodeiterator/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [String](../../../system/string/)
* Klasse [XPathNavigator](../)
* Klasse [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasse [XPathExpression](../../xpathexpression/)
* Klasse [XPathNodeIterator](../../xpathnodeiterator/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)