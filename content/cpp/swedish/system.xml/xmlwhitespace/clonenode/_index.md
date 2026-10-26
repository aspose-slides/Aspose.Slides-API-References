---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en duplicering av den här noden.
type: docs
weight: 79
url: /sv/system.xml/xmlwhitespace/clonenode/
---
## XmlWhitespace::CloneNode(bool) metod


Skapar en duplicering av den här noden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlWhitespace::CloneNode(bool deep) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** för att rekursivt klona underträdet under den angivna noden; **false** för att klona endast själva noden. För whitespace-noder inkluderar den klonade noden alltid datavärdet, oavsett parameterinställning. |

### Returvärde

Den klonade noden.

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlWhitespace](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)