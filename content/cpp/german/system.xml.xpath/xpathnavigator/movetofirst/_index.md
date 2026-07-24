---
title: MoveToFirst()
second_title: Aspose.Slides für C++ API-Referenz
description: Verschiebt den XPathNavigator zum ersten Geschwisterknoten des aktuellen Knotens.
type: docs
weight: 612
url: /de/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() Methode


Verschiebt das [XPathNavigator](../) zum ersten Geschwisterknoten des aktuellen Knotens.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### Rückgabewert

**true**, wenn das [XPathNavigator](../) erfolgreich zum ersten Geschwisterknoten des aktuellen Knotens verschoben wird; **false**, wenn kein erstes Geschwister existiert oder wenn das [XPathNavigator](../) derzeit auf einem Attributknoten positioniert ist. Wenn das [XPathNavigator](../) bereits auf dem ersten Geschwister positioniert ist, wird [XPathNavigator](../) **true** zurückgeben und seine Position nicht ändern. Wenn [XPathNavigator::MoveToFirst](./) **false** zurückgibt, weil kein erstes Geschwister vorhanden ist, oder wenn [XPathNavigator](../) derzeit auf einem Attribut positioniert ist, bleibt die Position des [XPathNavigator](../) unverändert.

## Siehe auch

* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)