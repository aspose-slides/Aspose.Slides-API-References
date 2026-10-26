---
title: MoveToNext()
second_title: Aspose.Slides für C++ API Referenz
description: Wenn in einer abgeleiteten Klasse überschrieben, verschiebt das XPathNavigator zum nächsten Geschwisterknoten des aktuellen Knotens.
type: docs
weight: 586
url: /de/system.xml.xpath/xpathnavigator/movetonext/
---
## XPathNavigator::MoveToNext() Methode

Wenn in einer abgeleiteten Klasse überschrieben, verschiebt das [XPathNavigator](../) zum nächsten Geschwisterknoten des aktuellen Knotens.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext()=0
```

### Rückgabewert

**true** wenn die [XPathNavigator](../) erfolgreich zum nächsten Geschwisterknoten bewegt wird; andernfalls **false**, wenn keine weiteren Geschwister mehr vorhanden sind oder wenn die [XPathNavigator](../) derzeit auf einem Attributknoten positioniert ist. Wenn **false**, bleibt die Position der [XPathNavigator](../) unverändert.

## XPathNavigator::MoveToNext(String, String) Methode

Verschiebt das [XPathNavigator](../) zum nächsten Geschwisterknoten mit dem angegebenen lokalen Namen und Namespace-URI.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(String localName, String namespaceURI)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Der lokale Name des nächsten Geschwisterknotens, zu dem verschoben werden soll. |
| namespaceURI | [String](../../../system/string/) | Der Namespace-URI des nächsten Geschwisterknotens, zu dem verschoben werden soll. |

### Rückgabewert

**true** wenn die [XPathNavigator](../) erfolgreich zum nächsten Geschwisterknoten bewegt wird; **false**, wenn keine weiteren Geschwister mehr vorhanden sind oder wenn die [XPathNavigator](../) derzeit auf einem Attributknoten positioniert ist. Wenn **false**, bleibt die Position der [XPathNavigator](../) unverändert.

## XPathNavigator::MoveToNext(XPathNodeType) Methode

Verschiebt das [XPathNavigator](../) zum nächsten Geschwisterknoten des aktuellen Knotens, der dem angegebenen XPathNodeType entspricht.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToNext(XPathNodeType type)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Der XPathNodeType des Geschwisterknotens, zu dem verschoben werden soll. |

### Rückgabewert

**true** wenn die [XPathNavigator](../) erfolgreich zum nächsten Geschwisterknoten bewegt wird; andernfalls **false**, wenn keine weiteren Geschwister mehr vorhanden sind oder wenn die [XPathNavigator](../) derzeit auf einem Attributknoten positioniert ist. Wenn **false**, bleibt die Position der [XPathNavigator](../) unverändert.

## Siehe auch

* Aufzählung [XPathNodeType](../../xpathnodetype/)
* Klasse [XPathNavigator](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)