---
title: CloneNode()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den här noden.
type: docs
weight: 157
url: /sv/system.xml/xmldeclaration/clonenode/
---
## XmlDeclaration::CloneNode(bool) metod

Skapar en kopia av den här noden.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDeclaration::CloneNode(bool deep) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. Because [XmlDeclaration](../) nodes do not have children, the cloned node always includes the data value, regardless of the parameter setting. |

### Returvärde

Den klonade noden.

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlNode](../../xmlnode/)
* Klass [XmlDeclaration](../)
* Namnrymd [System::Xml](../../)
* Bibliotek [Aspose.Slides](../../../)