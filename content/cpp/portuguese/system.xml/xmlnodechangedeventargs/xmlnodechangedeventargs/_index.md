---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides para C++ Referência da API
description: Inicializa uma nova instância da classe XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /pt/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

Inicializa uma nova instância da classe [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | O [XmlNode](../../xmlnode/) que gerou o evento. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | O antigo pai [XmlNode](../../xmlnode/) do [XmlNode](../../xmlnode/) que gerou o evento. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | O novo pai [XmlNode](../../xmlnode/) do [XmlNode](../../xmlnode/) que gerou o evento. |
| oldValue | const [String](../../../system/string/)\& | O valor antigo do [XmlNode](../../xmlnode/) que gerou o evento. |
| newValue | const [String](../../../system/string/)\& | O novo valor do [XmlNode](../../xmlnode/) que gerou o evento. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | O XmlNodeChangedAction. |

## Veja Também

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)