---
title: get_OldValue()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací původní hodnotu uzlu.
type: docs
weight: 53
url: /cs/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() metoda


Vrací původní hodnotu uzlu.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Návratová hodnota

Původní hodnota uzlu. Tato metoda vrací **nullptr**, pokud uzel není ani atributem, ani textovým uzlem, nebo pokud je uzel vkládán. Pokud je volána během události **XmlDocument::NodeChanging**, **get_OldValue** vrátí aktuální hodnotu uzlu, která bude nahrazena, pokud změna bude úspěšná. Pokud je volána během události **XmlDocument::NodeChanged**, **get_OldValue** vrátí hodnotu uzlu před změnou.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeChangedEventArgs](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)