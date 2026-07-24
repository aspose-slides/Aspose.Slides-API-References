---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides für C++ API Referenz
description: Initialisiert eine neue Instanz der XmlNodeChangedEventArgs-Klasse.
type: docs
weight: 79
url: /de/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

Initialisiert eine neue Instanz der Klasse [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Der [XmlNode](../../xmlnode/), der das Ereignis ausgelöst hat. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Der alte übergeordnete [XmlNode](../../xmlnode/) des [XmlNode](../../xmlnode/), der das Ereignis ausgelöst hat. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Der neue übergeordnete [XmlNode](../../xmlnode/) des [XmlNode](../../xmlnode/), der das Ereignis ausgelöst hat. |
| oldValue | const [String](../../../system/string/)\& | Der alte Wert des [XmlNode](../../xmlnode/), der das Ereignis ausgelöst hat. |
| newValue | const [String](../../../system/string/)\& | Der neue Wert des [XmlNode](../../xmlnode/), der das Ereignis ausgelöst hat. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | Die XmlNodeChangedAction. |

## Siehe auch

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNodeChangedEventArgs](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)