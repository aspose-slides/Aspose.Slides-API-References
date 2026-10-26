---
title: XmlNodeChangedEventArgs()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /it/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) costruttore


Inizializza una nuova istanza della classe [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Il [XmlNode](../../xmlnode/) che ha generato l'evento. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Il genitore precedente [XmlNode](../../xmlnode/) del [XmlNode](../../xmlnode/) che ha generato l'evento. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Il nuovo genitore [XmlNode](../../xmlnode/) del [XmlNode](../../xmlnode/) che ha generato l'evento. |
| oldValue | const [String](../../../system/string/)\& | Il vecchio valore del [XmlNode](../../xmlnode/) che ha generato l'evento. |
| newValue | const [String](../../../system/string/)\& | Il nuovo valore del [XmlNode](../../xmlnode/) che ha generato l'evento. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | L'XmlNodeChangedAction. |

## Vedi anche

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)