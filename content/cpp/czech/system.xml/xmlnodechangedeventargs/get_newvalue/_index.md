---
title: get_NewValue()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací novou hodnotu uzlu.
type: docs
weight: 66
url: /cs/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() metoda

Vrací novou hodnotu uzlu.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Návratová hodnota

Nová hodnota uzlu. Tato metoda vrací **nullptr**, pokud uzel není ani atributem, ani textovým uzlem, nebo pokud je uzel odstraňován. Pokud je volána během události **XmlDocument::NodeChanging**, **get_NewValue** vrací hodnotu uzlu, pokud je změna úspěšná. Pokud je volána během události **XmlDocument::NodeChanged**, **get_NewValue** vrací aktuální hodnotu uzlu.

## Viz také

* Třída [String](../../../system/string/)
* Třída [XmlNodeChangedEventArgs](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)