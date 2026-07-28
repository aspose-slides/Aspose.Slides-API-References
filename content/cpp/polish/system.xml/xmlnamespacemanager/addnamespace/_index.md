---
title: AddNamespace()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Dodaje podaną przestrzeń nazw do kolekcji.
type: docs
weight: 66
url: /pl/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) metoda

Dodaje podaną przestrzeń nazw do kolekcji.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Prefiks, który ma być powiązany z dodawaną przestrzenią nazw. Użyj [String::Empty](../../../system/string/empty/) aby dodać domyślną przestrzeń nazw. Jeśli [XmlNamespaceManager](../) będzie używany do rozwiązywania przestrzeni nazw w wyrażeniu XML Path Language ([XPath](../../../system.xml.xpath/)), należy podać prefiks. Jeśli wyrażenie [XPath](../../../system.xml.xpath/) nie zawiera prefiksu, przyjmuje się, że identyfikator URI przestrzeni nazw jest pustą przestrzenią. Aby uzyskać więcej informacji o wyrażeniach [XPath](../../../system.xml.xpath/) i [XmlNamespaceManager](../), zobacz metody XmlNode::SelectNodes(String) i XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | [String](../../../system/string/) | Przestrzeń nazw do dodania. |

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [XmlNamespaceManager](../)
* Przestrzeń nazw [System::Xml](../../)
* Biblioteka [Aspose.Slides](../../../)