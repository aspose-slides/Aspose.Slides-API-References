---
title: CloneNode()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří duplikát tohoto uzlu.
type: docs
weight: 92
url: /cs/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) method

Vytvoří duplikát tohoto uzlu.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. Pro uzly [XmlEntityReference](../) tato metoda vždy vrací uzel referenční entity bez potomků. Náhradní text je nastaven, když je uzel vložen do nadřazeného uzlu. |

### Návratová hodnota

Duplikovaný uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [XmlEntityReference](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)