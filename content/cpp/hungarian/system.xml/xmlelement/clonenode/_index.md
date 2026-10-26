---
title: CloneNode()
second_title: Aspose.Slides for C++ API referencia
description: Létrehoz egy másolatot erről a csomópontról.
type: docs
weight: 196
url: /hu/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) metódus


Létrehoz egy másolatot erről a csomópontról.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true** rekurzívan klónozza a megadott csomópont alatti részfát; **false** csak a csomópontot magát klónozza (és attribútumait, ha a csomópont egy [XmlElement](../)). |

### Visszatérési érték

A klónozott csomópont.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlElement](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)