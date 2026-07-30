---
title: get_LocalName()
second_title: Aspose.Slides pro C++ – reference API
description: Když je v odvozené třídě přepsána, získá lokální název aktuálního uzlu.
type: docs
weight: 40
url: /cs/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() metoda

Když je v odvozené třídě přepsána, získá lokální název aktuálního uzlu.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### Návratová hodnota

Název aktuálního uzlu bez předpony. Například, **LocalName** je **book** pro element **<bk:book>**. Pro typy uzlů, které nemají název (jako **[Text](../../../system.text/)**, **Comment**, a tak dále), tato metoda vrací [String::Empty](../../../system/string/empty/).

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)