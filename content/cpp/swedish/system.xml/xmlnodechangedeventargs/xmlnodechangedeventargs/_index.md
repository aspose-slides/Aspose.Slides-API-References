---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av klassen XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /sv/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) konstruktor


Initierar en ny instans av klassen [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Den [XmlNode](../../xmlnode/) som genererade händelsen. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Den gamla föräldern [XmlNode](../../xmlnode/) till [XmlNode](../../xmlnode/) som genererade händelsen. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Den nya föräldern [XmlNode](../../xmlnode/) till [XmlNode](../../xmlnode/) som genererade händelsen. |
| oldValue | const [String](../../../system/string/)\& | Det gamla värdet av [XmlNode](../../xmlnode/) som genererade händelsen. |
| newValue | const [String](../../../system/string/)\& | Det nya värdet av [XmlNode](../../xmlnode/) som genererade händelsen. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | XmlNodeChangedAction. |

## Se även

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [String](../../../system/string/)
* Klass [XmlNodeChangedEventArgs](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)