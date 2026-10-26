---
title: Compile()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Kompiluje określone wyrażenie XPath i zwraca obiekt XPathExpression reprezentujący wyrażenie XPath.
type: docs
weight: 66
url: /pl/system.xml.xpath/xpathexpression/compile/
---
## XPathExpression::Compile(const String\&) metoda


Kompiluje określone wyrażenie [XPath](../../) i zwraca obiekt [XPathExpression](../) reprezentujący wyrażenie [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Wyrażenie [XPath](../../). |

### Wartość zwracana

Obiekt [XPathExpression](../).

## XPathExpression::Compile(const String\&, const SharedPtr\<IXmlNamespaceResolver\>\&) metoda


Kompiluje określone wyrażenie [XPath](../../), z obiektem [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) określonym do rozwiązywania przestrzeni nazw, i zwraca obiekt [XPathExpression](../) reprezentujący wyrażenie [XPath](../../).

```cpp
static SharedPtr<XPathExpression> System::Xml::XPath::XPathExpression::Compile(const String &xpath, const SharedPtr<IXmlNamespaceResolver> &nsResolver)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | Wyrażenie [XPath](../../). |
| nsResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Obiekt implementujący interfejs [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) do rozwiązywania przestrzeni nazw. |

### Wartość zwracana

Obiekt [XPathExpression](../).

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XPathExpression](../)
* Klasa [String](../../../system/string/)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Przestrzeń nazw [System::Xml::XPath](../../)
* Biblioteka [Aspose.Slides](../../../)