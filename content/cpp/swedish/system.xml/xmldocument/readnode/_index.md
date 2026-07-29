---
title: ReadNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett XmlNode-objekt baserat på informationen i XmlReader. Läsaren måste vara placerad på en nod eller ett attribut.
type: docs
weight: 495
url: /sv/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) method


Skapar ett [XmlNode](../../xmlnode/)-objekt baserat på informationen i [XmlReader](../../xmlreader/). Läsaren måste vara placerad på en nod eller ett attribut.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML-källan. |

### Returvärde

Det nya [XmlNode](../../xmlnode/) eller **nullptr** om inga fler noder finns.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlReader](../../xmlreader/)
* Klass [XmlDocument](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)