---
title: ReadAttributeValue()
second_title: Aspose.Slides pro C++ API Reference
description: Rozebere hodnotu atributu na jeden nebo více uzlů Text, EntityReference nebo EndEntity.
type: docs
weight: 508
url: /cs/system.xml/xmlvalidatingreader/readattributevalue/
---
## XmlValidatingReader::ReadAttributeValue() metoda

Rozebere hodnotu atributu na jeden nebo více **[Text](../../../system.text/)**, **EntityReference** nebo **EndEntity** uzlů.

```cpp
bool System::Xml::XmlValidatingReader::ReadAttributeValue() override
```

### Návratová hodnota

**true** pokud existují uzly k vrácení. **false** pokud čtečka není umístěna na uzel atributu při prvním volání nebo pokud byly přečteny všechny hodnoty atributů. Prázdný atribut, například **misc=\"\"**, vrací **true** s jediným uzlem s hodnotou [String::Empty](../../../system/string/empty/).

## Viz také

* Třída [XmlValidatingReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)