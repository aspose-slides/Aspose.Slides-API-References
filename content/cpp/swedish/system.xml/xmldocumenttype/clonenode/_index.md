---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en duplicering av denna nod.
type: docs
weight: 118
url: /sv/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) metod

Skapar en duplicering av denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** för att rekursivt klona underträdet under den angivna noden; **false** för att endast klona själva noden. För dokumenttypnoder inkluderar den klonade noden alltid underträdet, oavsett parameterinställning. |

### Returvärde

Den klonade noden.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlDocumentType](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)