---
title: XmlNodeChangedEventArgs()
second_title: Referencia de API de Aspose.Slides para C++
description: Inicializa una nueva instancia de la clase XmlNodeChangedEventArgs.
type: docs
weight: 79
url: /es/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor


Inicializa una nueva instancia de la clase [XmlNodeChangedEventArgs](../).

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | El [XmlNode](../../xmlnode/) que generó el evento. |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | El padre anterior [XmlNode](../../xmlnode/) del [XmlNode](../../xmlnode/) que generó el evento. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | El nuevo padre [XmlNode](../../xmlnode/) del [XmlNode](../../xmlnode/) que generó el evento. |
| oldValue | const [String](../../../system/string/)\& | El valor antiguo del [XmlNode](../../xmlnode/) que generó el evento. |
| newValue | const [String](../../../system/string/)\& | El valor nuevo del [XmlNode](../../xmlnode/) que generó el evento. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | El XmlNodeChangedAction. |

## Ver también

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [String](../../../system/string/)
* Clase [XmlNodeChangedEventArgs](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)