---
title: WriteNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, kopiert sie alles vom Reader zum Writer und verschiebt den Reader an den Anfang des nächsten Geschwisterelements.
type: docs
weight: 430
url: /de/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) Methode


Wenn in einer abgeleiteten Klasse überschrieben, kopiert sie alles vom Reader zum Writer und verschiebt den Reader an den Anfang des nächsten Geschwisterelements.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Der [XmlReader](../../xmlreader/) zum Lesen. |
| defattr | **bool** | **true** zum Kopieren der Standardattribute aus dem [XmlReader](../../xmlreader/); andernfalls **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) Methode


Kopiert alles vom XPathNavigator-Objekt zum Writer. Die Position des XPathNavigator bleibt unverändert.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Der XPathNavigator zum Kopieren. |
| defattr | **bool** | **true** zum Kopieren der Standardattribute; andernfalls **false**. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlReader](../../xmlreader/)
* Klasse [XmlWriter](../)
* Klasse [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)