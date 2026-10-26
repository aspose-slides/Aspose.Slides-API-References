---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en duplikat av den här noden. Notationsnoder kan inte klonas. Att anropa den här metoden på ett XmlNotation-objekt kastar ett undantag.
type: docs
weight: 118
url: /sv/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) metod

Skapar en duplikat av den här noden. Notationsnoder kan inte klonas. Att anropa den här metoden på ett [XmlNotation](../)-objekt kastar ett undantag.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** för att rekursivt klona underträdet under den angivna noden; **false** för att bara klona själva noden. |

### Returvärde

En [XmlNode](../../xmlnode/)-kopia av noden som metoden anropas på.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlNotation](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)