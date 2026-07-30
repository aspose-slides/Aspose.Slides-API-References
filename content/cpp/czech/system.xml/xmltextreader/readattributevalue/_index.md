---
title: ReadAttributeValue()
second_title: Aspose.Slides pro C++ API Reference
description: Analyzuje hodnotu atributu na jeden nebo více uzlů Text, EntityReference nebo EndEntity.
type: docs
weight: 560
url: /cs/system.xml/xmltextreader/readattributevalue/
---
## XmlTextReader::ReadAttributeValue() metoda

Analyzuje hodnotu atributu na jeden nebo více uzlů **[Text](../../../system.text/)**, **EntityReference** nebo **EndEntity**.

```cpp
bool System::Xml::XmlTextReader::ReadAttributeValue() override
```

### Návratová hodnota

**true** pokud existují uzly k vrácení. **false** pokud čtečka není umístěna na uzlu atributu při prvním volání nebo pokud byly všechny hodnoty atributů přečteny. Prázdný atribut, například **misc=\"\"**, vrátí **true** s jedním uzlem s hodnotou [String::Empty](../../../system/string/empty/).

## Viz také

* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)