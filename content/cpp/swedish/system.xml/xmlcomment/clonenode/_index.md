---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en duplicat av den här noden.
type: docs
weight: 40
url: /sv/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) metod

Skapar en duplicat av den här noden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** för att rekursivt klona delträdet under den angivna noden; **false** för att bara klona själva noden. Eftersom kommentarnoder inte har barn, inkluderar den klonade noden alltid textinnehållet, oavsett parameterinställning. |

### Returvärde

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlComment](../)
* Namnrymd [System::Xml](../../)
* Library [Aspose.Slides](../../../)