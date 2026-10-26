---
title: XmlNodeChangedEventArgs()
second_title: Aspose.Slides C++ API-referencia
description: Új példányt hoz létre az XmlNodeChangedEventArgs osztályból.
type: docs
weight: 79
url: /hu/system.xml/xmlnodechangedeventargs/xmlnodechangedeventargs/
---
## XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const SharedPtr\<XmlNode\>\&, const String\&, const String\&, XmlNodeChangedAction) constructor

Inicializál egy új példányt a [XmlNodeChangedEventArgs](../) osztályból.

```cpp
System::Xml::XmlNodeChangedEventArgs::XmlNodeChangedEventArgs(const SharedPtr<XmlNode> &node, const SharedPtr<XmlNode> &oldParent, const SharedPtr<XmlNode> &newParent, const String &oldValue, const String &newValue, XmlNodeChangedAction action)
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Az eseményt generáló [XmlNode](../../xmlnode/). |
| oldParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | A korábbi szülő [XmlNode](../../xmlnode/) a [XmlNode](../../xmlnode/)-nek, amely eseményt generált. |
| newParent | const [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\>\& | Az új szülő [XmlNode](../../xmlnode/) a [XmlNode](../../xmlnode/)-nek, amely eseményt generált. |
| oldValue | const [String](../../../system/string/)\& | Az [XmlNode](../../xmlnode/) régi értéke, amely eseményt generált. |
| newValue | const [String](../../../system/string/)\& | Az [XmlNode](../../xmlnode/) új értéke, amely eseményt generált. |
| action | [XmlNodeChangedAction](../../xmlnodechangedaction/) | Az XmlNodeChangedAction. |

## See Also

* Enum [XmlNodeChangedAction](../../xmlnodechangedaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNodeChangedEventArgs](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)