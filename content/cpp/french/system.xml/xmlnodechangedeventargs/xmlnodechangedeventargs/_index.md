---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides pour C++ Référence API
description: Initialise une nouvelle instance de la classe XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /fr/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

Initialise une nouvelle instance de la classe [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Le [XmlNode](../../xmlnode/) qui a généré l'événement. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | L'ancien parent [XmlNode](../../xmlnode/) du [XmlNode](../../xmlnode/) qui a généré l'événement. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Le nouveau parent [XmlNode](../../xmlnode/) du [XmlNode](../../xmlnode/) qui a généré l'événement. |
| oldValue | const [String](../../../system/string/)\& | L'ancienne valeur du [XmlNode](../../xmlnode/) qui a généré l'événement. |
| newValue | const [String](../../../system/string/)\& | La nouvelle valeur du [XmlNode](../../xmlnode/) qui a généré l'événement. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | Le XmlNodeChangedAction. |

## Voir aussi

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [String](../../../system/string/)
* Classe [XmlNodeChangedEventArgs](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)