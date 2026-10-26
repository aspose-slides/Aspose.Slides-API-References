---
title: AppendChild()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein XmlWriter-Objekt zurück, das verwendet wird, um ein oder mehrere neue Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens zu erstellen.
type: docs
weight: 885
url: /de/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() Methode


Gibt ein [XmlWriter](../../../system.xml/xmlwriter/)-Objekt zurück, das verwendet wird, um ein oder mehrere neue Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens zu erstellen.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### Rückgabewert

Ein [XmlWriter](../../../system.xml/xmlwriter/)-Objekt, das verwendet wird, um neue Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens zu erstellen.

## XPathNavigator::AppendChild(String) Methode


Erstellt einen neuen Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens unter Verwendung der angegebenen XML-Datenzeichenkette.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Die XML-Datenzeichenkette für den neuen Kindknoten. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) Methode


Erstellt einen neuen Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens unter Verwendung des XML-Inhalts des angegebenen [XmlReader](../../../system.xml/xmlreader/)-Objekts.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ein [XmlReader](../../../system.xml/xmlreader/)-Objekt, das auf den XML-Daten für den neuen Kindknoten positioniert ist. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) Methode


Erstellt einen neuen Kindknoten am Ende der Liste der Kindknoten des aktuellen Knotens unter Verwendung der im angegebenen [XPathNavigator](../) enthaltenen Knoten.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ein [XPathNavigator](../)-Objekt, das auf den Knoten positioniert ist, der als neuer Kindknoten hinzugefügt werden soll. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)