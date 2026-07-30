---
title: get_LocalName()
second_title: Aspose.Slides pro C++ referenci API
description: Vrací lokální název aktuálního uzlu.
type: docs
weight: 27
url: /cs/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() metoda


Vrací lokální název aktuálního uzlu.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### Vrácená hodnota

Název aktuálního uzlu po odebrání předpony. Například **LocalName** je **book** pro prvek **<bk:book>**. Pro typy uzlů, které nemají název (například **[Text](../../../system.text/)**, **Comment** a tak dále), tato metoda vrací [String::Empty](../../../system/string/empty/).

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)