---
title: CloneNode()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza ennek a csomópontnak a másolatát.
type: docs
weight: 40
url: /hu/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(bool) metódus

Létrehozza ennek a csomópontnak a másolatát.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true** a megadott csomópont alatti részfa rekurzív klónozásához; **false** csak a csomópont önmagának klónozásához. Mivel a megjegyzés csomópontoknak nincsenek gyermekeik, a klónozott csomópont mindig tartalmazza a szövegtartalmat, a paraméter beállításától függetlenül. |

### Visszatérési érték

A klónozott csomópont.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlComment](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)