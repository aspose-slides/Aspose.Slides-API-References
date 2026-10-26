---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den här noden.
type: docs
weight: 53
url: /sv/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) metod


Skapar en duplikat av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** för att rekursivt klona underträdet under den angivna noden; **false** för att bara klona själva noden. Eftersom CDATA-noder inte har barn, oavsett parameterinställning, kommer den klonade noden alltid att inkludera datainnehållet. |

### Returvärde

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlCDataSection](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)