---
title: SelectSingleNode()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Wybiera pojedynczy węzeł w XPathNavigator przy użyciu określonego zapytania XPath.
type: docs
weight: 781
url: /pl/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) metoda

Wybiera pojedynczy węzeł w [XPathNavigator](../) przy użyciu określonego zapytania [XPath](../../).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Obiekt [String](../../../system/string/) reprezentujący wyrażenie [XPath](../../). |

### Wartość zwracana

Obiekt [XPathNavigator](../) zawierający pierwszy pasujący węzeł dla określonego zapytania [XPath](../../); w przeciwnym razie **nullptr**, jeśli nie ma wyników zapytania.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) metoda

Wybiera pojedynczy węzeł w obiekcie [XPathNavigator](../) przy użyciu określonego zapytania [XPath](../../) z obiektem [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) służącym do rozwiązywania prefiksów przestrzeni nazw.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Obiekt [String](../../../system/string/) reprezentujący wyrażenie [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) służący do rozwiązywania prefiksów przestrzeni nazw w zapytaniu [XPath](../../). |

### Wartość zwracana

Obiekt [XPathNavigator](../) zawierający pierwszy pasujący węzeł dla określonego zapytania [XPath](../../); w przeciwnym razie **nullptr**, jeśli nie ma wyników zapytania.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) metoda

Wybiera pojedynczy węzeł w [XPathNavigator](../) przy użyciu określonego obiektu [XPathExpression](../../xpathexpression/).

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Obiekt [XPathExpression](../../xpathexpression/) zawierający skompilowane zapytanie [XPath](../../). |

### Wartość zwracana

Obiekt [XPathNavigator](../) zawierający pierwszy pasujący węzeł dla określonego zapytania [XPath](../../); w przeciwnym razie **nullptr**, jeśli nie ma wyników zapytania.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathNavigator](../)
* Klasa [String](../../../system/string/)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasa [XPathExpression](../../xpathexpression/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)