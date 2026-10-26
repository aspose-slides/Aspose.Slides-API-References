---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en duplicat av den här noden. Entitetsnoder kan inte klonas. Att anropa den här metoden på ett XmlEntity-objekt kastar ett undantag.
type: docs
weight: 170
url: /sv/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) metod

Skapar en kopia av den här noden. Entitetsnoder kan inte klonas. Att anropa den här metoden på ett [XmlEntity](../)-objekt kastar ett undantag.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att bara klona själva noden. |

### Returvärde

En kopia av [XmlNode](../../xmlnode/) från vilken metoden anropas.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlEntity](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)