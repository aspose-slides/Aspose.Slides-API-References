---
title: CloneNode()
second_title: Aspose.Slides C++ API Referenciája
description: Létrehozza ennek a csomópontnak a másolatát. A Notation csomópontok nem klónozhatók. Ennek a metódusnak a meghívása egy XmlNotation objektumon kivételt dob.
type: docs
weight: 118
url: /hu/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) metódus


Létrehozza ennek a csomópontnak a másolatát. A Notation csomópontok nem klónozhatók. Ennek a metódusnak a meghívása egy [XmlNotation](../) objektumon kivételt dob.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true** a megadott csomópont alatti részfa rekurzív klónozásához; **false** csak a csomópontot klónozza. |

### Visszatérési érték

A [XmlNode](../../xmlnode/) másolat arról a csomópontról, amelyről a metódust meghívják.

## Lásd még

* typedef [SharedPtr](../../../system/sharedptr/)
* osztály [XmlNode](../../xmlnode/)
* osztály [XmlNotation](../)
* névtér [System::Xml](../../)
* könyvtár [Aspose.Slides](../../../)