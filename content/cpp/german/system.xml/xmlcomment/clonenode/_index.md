---
title: CloneNode()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Duplikat dieses Knotens.
type: docs
weight: 40
url: /de/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) Methode


Erstellt ein Duplikat dieses Knotens.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** zum rekursiven Klonen des Teilbaums unter dem angegebenen Knoten; **false** zum Klonen nur des Knotens selbst. Da Kommentar-Knoten keine Kinder haben, enthält der geklonte Knoten immer den Textinhalt, unabhängig von der Parameter-Einstellung. |

### Return Value

Der geklonte Knoten.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [XmlComment](../)
* Namensraum [System::Xml](../../)
* Bibliothek [Aspose.Slides](../../../)