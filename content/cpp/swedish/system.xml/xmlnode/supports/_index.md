---
title: Supports()
second_title: Aspose.Slides för C++ API-referens
description: Testar om DOM-implementationen implementerar en specifik funktion.
type: docs
weight: 482
url: /sv/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) metod


Testar om DOM-implementationen implementerar en specifik funktion.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Paketnamnet för funktionen som ska testas. Detta namn är inte skiftlägeskänsligt. |
| version | [String](../../../system/string/) | Versionsnumret för paketnamnet som ska testas. Om versionen inte specificeras (null) innebär stöd för någon version av funktionen att metoden returnerar true. |

### Returvärde

**true** om funktionen är implementerad i den angivna versionen; annars **false**.
## Anmärkningar



Följande tabell beskriver kombinationerna som returnerar **true**. 

| Funktion | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Se också

* Klass [String](../../../system/string/)
* Klass [XmlNode](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)