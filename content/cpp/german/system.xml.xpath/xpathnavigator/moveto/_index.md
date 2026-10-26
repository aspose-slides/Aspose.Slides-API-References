---
title: MoveTo()
second_title: Aspose.Slides für C++ API-Referenz
description: Wenn sie in einer abgeleiteten Klasse überschrieben wird, bewegt sie den XPathNavigator an dieselbe Position wie der angegebene XPathNavigator.
type: docs
weight: 664
url: /de/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) Methode


Wenn sie in einer abgeleiteten Klasse überschrieben wird, bewegt [XPathNavigator](../) an dieselbe Position wie das angegebene [XPathNavigator](../).

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Der [XPathNavigator](../), der auf dem Knoten positioniert ist, zu dem Sie wechseln möchten. |

### Rückgabewert

**true** wenn das [XPathNavigator](../) erfolgreich an dieselbe Position wie das angegebene [XPathNavigator](../) bewegt wird; andernfalls **false**. Wenn **false**, bleibt die Position des [XPathNavigator](../) unverändert.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XPathNavigator](../)
* Namensraum [System::Xml::XPath](../../)
* Bibliothek [Aspose.Slides](../../../)