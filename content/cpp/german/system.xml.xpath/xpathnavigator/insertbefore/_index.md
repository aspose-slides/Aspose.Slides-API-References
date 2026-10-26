---
title: InsertBefore()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein XmlWriter-Objekt zurück, das verwendet wird, um einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten zu erstellen.
type: docs
weight: 911
url: /de/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() Methode


Gibt ein [XmlWriter](../../../system.xml/xmlwriter/)-Objekt zurück, das verwendet wird, um einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten zu erstellen.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### Rückgabewert

Ein [XmlWriter](../../../system.xml/xmlwriter/)-Objekt, das verwendet wird, um einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten zu erstellen.

## XPathNavigator::InsertBefore(String) Methode


Erstellt einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten unter Verwendung der angegebenen XML-Zeichenfolge.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Die XML-Datenzeichenfolge für den neuen Geschwisterknoten. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) Methode


Erstellt einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten unter Verwendung des XML-Inhalts des angegebenen [XmlReader](../../../system.xml/xmlreader/)-Objekts.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ein [XmlReader](../../../system.xml/xmlreader/)-Objekt, das auf den XML-Daten für den neuen Geschwisterknoten positioniert ist. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) Methode


Erstellt einen neuen Geschwisterknoten vor dem aktuell ausgewählten Knoten unter Verwendung der Knoten im angegebenen [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ein [XPathNavigator](../)-Objekt, das auf den Knoten positioniert ist, der als neuer Geschwisterknoten hinzugefügt werden soll. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)