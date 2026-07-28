---
title: CloneNode()
second_title: Aspose.Slides for C++ API referencia
description: Létrehoz egy másolatot erről a csomópontról. Az Entity csomópontok nem klónozhatók. Ennek a metódusnak az XmlEntity objektumon való meghívása kivételt dob.
type: docs
weight: 170
url: /hu/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) metódus


Létrehoz egy másolatot erről a csomópontról. Az Entity csomópontok nem klónozhatók. Ennek a metódusnak az [XmlEntity](../) objektumon való meghívása kivételt dob.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true** a megadott csomópont alatti részfa rekurzív klónozásához; **false** csak magát a csomópontot klónozza. |

### Visszatérési érték

A [XmlNode](../../xmlnode/) másolata, amelyről a metódus meghívásra kerül.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlEntity](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)