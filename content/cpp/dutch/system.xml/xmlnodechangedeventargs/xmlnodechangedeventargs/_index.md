---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de XmlNodeChangedEventArgs klasse.
type: docs
weight: 79
url: /nl/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

Initialiseert een nieuw exemplaar van de [XmlNodeChangedEventArgs](../) klasse.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | De [XmlNode](../../xmlnode/) die het evenement heeft gegenereerd. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | De oude ouder [XmlNode](../../xmlnode/) van de [XmlNode](../../xmlnode/) die het evenement heeft gegenereerd. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | De nieuwe ouder [XmlNode](../../xmlnode/) van de [XmlNode](../../xmlnode/) die het evenement heeft gegenereerd. |
| oldValue | const [String](../../../system/string/)\& | De oude waarde van de [XmlNode](../../xmlnode/) die het evenement heeft gegenereerd. |
| newValue | const [String](../../../system/string/)\& | De nieuwe waarde van de [XmlNode](../../xmlnode/) die het evenement heeft gegenereerd. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | De XmlNodeChangedAction. |

## Zie ook

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlNodeChangedEventArgs](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)