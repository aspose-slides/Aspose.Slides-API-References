---
title: PrependChild()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till den angivna noden i början av listan med barnnoder för denna nod.
type: docs
weight: 261
url: /sv/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) metod

Lägger till den angivna noden i början av listan med barnnoder för denna nod.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | Den [XmlNode](../../xmlnode/) att lägga till. Om den är en [XmlDocumentFragment](../../xmldocumentfragment/), flyttas hela innehållet i dokumentfragmentet till barnlistan för denna nod. |

### Returvärde

Den [XmlNode](../../xmlnode/) som lades till.

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlAttribute](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)