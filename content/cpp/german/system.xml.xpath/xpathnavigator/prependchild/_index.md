---
title: PrependChild()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt ein XmlWriter-Objekt zurück, das zum Erstellen eines neuen Kindknotens am Anfang der Liste der Kindknoten des aktuellen Knotens verwendet wird.
type: docs
weight: 872
url: /de/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() Methode


Gibt ein [XmlWriter](../../../system.xml/xmlwriter/)-Objekt zurück, das zum Erstellen eines neuen Kindknotens am Anfang der Liste der Kindknoten des aktuellen Knotens verwendet wird.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```


### Rückgabewert

Ein [XmlWriter](../../../system.xml/xmlwriter/)-Objekt, das zum Erstellen eines neuen Kindknotens am Anfang der Liste der Kindknoten des aktuellen Knotens verwendet wird.

## XPathNavigator::PrependChild(String) Methode


Erstellt einen neuen Kindknoten am Anfang der Liste der Kindknoten des aktuellen Knotens unter Verwendung der angegebenen XML-Zeichenfolge.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Die XML-Datenzeichenfolge für den neuen Kindknoten. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) Methode


Erstellt einen neuen Kindknoten am Anfang der Liste der Kindknoten des aktuellen Knotens unter Verwendung des XML-Inhalts des angegebenen [XmlReader](../../../system.xml/xmlreader/)-Objekts.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Ein [XmlReader](../../../system.xml/xmlreader/)-Objekt, das auf die XML-Daten des neuen Kindknotens positioniert ist. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) Methode


Erstellt einen neuen Kindknoten am Anfang der Liste der Kindknoten des aktuellen Knotens unter Verwendung der Knoten im angegebenen [XPathNavigator](../)-Objekt.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Ein [XPathNavigator](../)-Objekt, das auf den Knoten positioniert ist, der als neuer Kindknoten hinzugefügt werden soll. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlWriter](../../../system.xml/xmlwriter/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Klasse [XmlReader](../../../system.xml/xmlreader/)
* Namensraum [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)