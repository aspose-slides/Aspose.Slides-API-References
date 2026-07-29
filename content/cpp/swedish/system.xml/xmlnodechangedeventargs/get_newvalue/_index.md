---
title: get_NewValue()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det nya värdet på noden.
type: docs
weight: 66
url: /sv/system.xml/xmlnodechangedeventargs/get_newvalue/
---
## XmlNodeChangedEventArgs::get_NewValue() metod


Returnerar det nya värdet på noden.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_NewValue()
```


### Returvärde

Det nya värdet på noden. Denna metod returnerar **nullptr** om noden varken är ett attribut eller en textnod, eller om noden tas bort. Om den anropas i en **XmlDocument::NodeChanging** händelse returnerar **get_NewValue** nodens värde om ändringen lyckas. Om den anropas i en **XmlDocument::NodeChanged** händelse returnerar **get_NewValue** nodens aktuella värde.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeChangedEventArgs](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)