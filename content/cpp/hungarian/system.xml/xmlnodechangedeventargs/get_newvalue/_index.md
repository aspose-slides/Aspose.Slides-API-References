---
title: get_NewValue()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a csomópont új értékét.
type: docs
weight: 66
url: /hu/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() metódus

Visszaadja a csomópont új értékét.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```

### Visszatérési érték

Az új érték a csomópont. Ez a metódus **nullptr** értéket ad vissza, ha a csomópont sem attribútum, sem szövegcímke, vagy ha a csomópont eltávolításra kerül. Ha egy **XmlDocument::NodeChanging** eseményben hívják, a **get_NewValue** visszaadja a csomópont értékét, ha a módosítás sikeres. Ha egy **XmlDocument::NodeChanged** eseményben hívják, a **get_NewValue** visszaadja a csomópont aktuális értékét.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeChangedEventArgs](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)