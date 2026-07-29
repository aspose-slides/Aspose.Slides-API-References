---
title: get_OldValue()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar det ursprungliga värdet av noden.
type: docs
weight: 53
url: /sv/system.xml/xmlnodechangedeventargs/get_oldvalue/
---
## XmlNodeChangedEventArgs::get_OldValue() metod


Returnerar det ursprungliga värdet av noden.

```cpp
String System::Xml::XmlNodeChangedEventArgs::get_OldValue()
```


### Returvärde

Det ursprungliga värdet av noden. Denna metod returnerar **nullptr** om noden varken är ett attribut eller en textnod, eller om noden håller på att infogas. Om den anropas i ett **XmlDocument::NodeChanging**-event, returnerar **get_OldValue** det aktuella värdet på noden som kommer att ersättas om ändringen lyckas. Om den anropas i ett **XmlDocument::NodeChanged**-event, returnerar **get_OldValue** värdet på noden före ändringen.

## Se även

* Klass [String](../../../system/string/)
* Klass [XmlNodeChangedEventArgs](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)