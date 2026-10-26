---
title: ReadAttributeValue()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Analyzuje hodnotu atributu na jeden nebo více Text, EntityReference nebo EndEntity uzlů.
type: docs
weight: 430
url: /cs/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() method

Analyzuje hodnotu atributu na jeden nebo více **[Text](../../../system.text/)**, **EntityReference** nebo **EndEntity** uzlů.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```

### Návratová hodnota

**true** pokud existují uzly k vrácení. **false** pokud čtečka není na uzlu atributu při prvním volání nebo pokud byly všechny hodnoty atributů přečteny. Prázdný atribut, například **misc=\"\"**, vrací **true** s jediným uzlem s hodnotou [String::Empty](../../../system/string/empty/).

## Viz také

* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)