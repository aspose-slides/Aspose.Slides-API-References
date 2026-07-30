---
title: SelectSingleNode()
second_title: Aspose.Slides pro C++ - reference API
description: Vybere jeden uzel v XPathNavigatoru pomocí specifikovaného dotazu XPath.
type: docs
weight: 781
url: /cs/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) metoda

Vybere jeden uzel v [XPathNavigator](../) pomocí specifikovaného dotazu [XPath](../../).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) reprezentující [XPath](../../) výraz. |

### Návratová hodnota

Objekt [XPathNavigator](../), který obsahuje první odpovídající uzel pro zadáný dotaz [XPath](../../); jinak **nullptr**, pokud nejsou žádné výsledky dotazu.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) metoda

Vybere jeden uzel v objektu [XPathNavigator](../) pomocí specifikovaného dotazu [XPath](../../) s objektem [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) určeným k rozlišení předpon jmenných prostorů.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/) reprezentující [XPath](../../) výraz. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Objekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) používaný k rozlišení předpon jmenných prostorů v dotazu [XPath](../../). |

### Návratová hodnota

Objekt [XPathNavigator](../), který obsahuje první odpovídající uzel pro dotaz [XPath](../../); jinak **nullptr**, pokud nejsou žádné výsledky dotazu.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) metoda

Vybere jeden uzel v [XPathNavigator](../) pomocí specifikovaného objektu [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Objekt [XPathExpression](../../xpathexpression/) obsahující zkompilovaný dotaz [XPath](../../). |

### Návratová hodnota

Objekt [XPathNavigator](../) obsahující první odpovídající uzel pro dotaz [XPath](../../); jinak **nullptr**, pokud nejsou žádné výsledky dotazu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XPathNavigator](../)
* Třída [String](../../../system/string/)
* Třída [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Třída [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)