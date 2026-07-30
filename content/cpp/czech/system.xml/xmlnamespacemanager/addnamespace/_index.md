---
title: AddNamespace()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Přidá zadaný jmenný prostor do kolekce.
type: docs
weight: 66
url: /cs/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) metoda

Přidá zadaný jmenný prostor do kolekce.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Předpona, která se má přiřadit k přidávanému jmennému prostoru. Pro přidání výchozího jmenného prostoru použijte [String::Empty](../../../system/string/empty/). Pokud bude [XmlNamespaceManager](../) používán pro řešení jmenných prostorů ve výrazu XML Path Language ([XPath](../../../system.xml.xpath/)), je nutné zadat předponu. Pokud výraz [XPath](../../../system.xml.xpath/) neobsahuje předponu, předpokládá se, že Uniform Resource Identifier (URI) jmenného prostoru je prázdný jmenný prostor. Další informace o výrazech [XPath](../../../system.xml.xpath/) a [XmlNamespaceManager](../) najdete v metodách XmlNode::SelectNodes(String) a XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | [String](../../../system/string/) | Jmenný prostor, který se má přidat. |

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNamespaceManager](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)