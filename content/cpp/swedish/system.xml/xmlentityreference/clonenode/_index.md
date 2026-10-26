---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett duplikat av den här noden.
type: docs
weight: 92
url: /sv/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) metod

Skapar ett duplikat av den här noden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** för att rekursivt klona underträdet under den angivna noden; **false** för att bara klona själva noden. För [XmlEntityReference](../)-noder returnerar denna metod alltid en entitetsreferensnod utan barn. Ersättningstexten sätts när noden infogas i en förälder. |

### Returvärde

Den klonade noden.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlEntityReference](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)