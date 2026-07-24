---
title: AddNamespace()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt den angegebenen Namensraum zur Sammlung hinzu.
type: docs
weight: 66
url: /de/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) Methode

Fügt den angegebenen Namensraum zur Sammlung hinzu.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Das Präfix, das dem hinzuzufügenden Namensraum zugeordnet werden soll. Verwenden Sie [String::Empty](../../../system/string/empty/) , um einen Standard-Namensraum hinzuzufügen. Wenn [XmlNamespaceManager](../) zum Auflösen von Namensräumen in einem XML Path Language ([XPath](../../../system.xml.xpath/)) Ausdruck verwendet wird, muss ein Präfix angegeben werden. Wenn ein [XPath](../../../system.xml.xpath/)-Ausdruck kein Präfix enthält, wird angenommen, dass der Uniform Resource Identifier (URI) des Namensraums der leere Namensraum ist. Weitere Informationen zu [XPath](../../../system.xml.xpath/)-Ausdrücken und [XmlNamespaceManager](../) finden Sie in den Methoden XmlNode::SelectNodes(String) und XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) Methoden. |
| uri | [String](../../../system/string/) | Der hinzuzufügende Namensraum. |

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [XmlNamespaceManager](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)