---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides pro C++ API Reference
description: Inicializuje novou instanci třídy XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /cs/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) konstruktor

Inicializuje novou instanci třídy [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | [XmlNode](../../xmlnode/), který vygeneroval událost. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Starý rodič [XmlNode](../../xmlnode/) [XmlNode](../../xmlnode/), který vygeneroval událost. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Nový rodič [XmlNode](../../xmlnode/) [XmlNode](../../xmlnode/), který vygeneroval událost. |
| oldValue | const [String](../../../system/string/)\& | Stará hodnota [XmlNode](../../xmlnode/), která vygenerovala událost. |
| newValue | const [String](../../../system/string/)\& | Nová hodnota [XmlNode](../../xmlnode/), která vygenerovala událost. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | Akce XmlNodeChangedAction. |

## Viz také

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)