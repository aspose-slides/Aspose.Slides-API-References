---
title: CloneNode()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy másolatot erről a csomópontról.
type: docs
weight: 118
url: /hu/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(bool) metódus


Létrehoz egy másolatot erről a csomópontról.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true**, ha rekurzívan klónozza a megadott csomópont alatti részfát; **false**, ha csak magát a csomópontot klónozza. Dokumentumtípus csomópontoknál a klónozott csomópont mindig tartalmazza a részfát, a paraméter beállításától függetlenül. |

## Visszatérési érték

A klónozott csomópont.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlDocumentType](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)