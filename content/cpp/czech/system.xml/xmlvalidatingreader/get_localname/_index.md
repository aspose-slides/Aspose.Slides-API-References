---
title: get_LocalName()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací lokální název aktuálního uzlu.
type: docs
weight: 27
url: /cs/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() metoda


Vrací lokální název aktuálního uzlu.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### Návratová hodnota

Název aktuálního uzlu bez předpony. Například **LocalName** je **book** pro prvek **<bk:book>**. U typů uzlů, které nemají název (jako **[Text](../../../system.text/)**, **Comment**, a tak dále), tato metoda vrací [String::Empty](../../../system/string/empty/).

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlValidatingReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)