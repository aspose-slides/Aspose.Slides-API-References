---
title: ReadAttributeValue()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Když je přepsána v odvozené třídě, rozebere hodnotu atributu na jeden nebo více uzlů Text, EntityReference nebo EndEntity.
type: docs
weight: 677
url: /cs/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() metoda


Při přepsání v odvozené třídě rozebere hodnotu atributu na jeden nebo více uzlů **[Text](../../../system.text/)**, **EntityReference** nebo **EndEntity**.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```


### Návratová hodnota

**true** pokud existují uzly k návratu. **false** pokud čtečka není umístěna na uzlu atributu při první výzvě nebo pokud byly přečteny všechny hodnoty atributu. Prázdný atribut, například **misc=\"\"**, vrací **true** s jediným uzlem s hodnotou [String::Empty](../../../system/string/empty/).

## Viz také

* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)