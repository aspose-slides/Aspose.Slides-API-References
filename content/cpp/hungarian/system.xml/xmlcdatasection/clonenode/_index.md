---
title: CloneNode()
second_title: Aspose.Slides C++ API Referenciája
description: Létrehoz egy másolatot erről a csomópontról.
type: docs
weight: 53
url: /hu/system.xml/xmlcdatasection/clonenode/
---
## XmlCDataSection::CloneNode(bool) method


Létrehoz egy másolatot erről a csomópontról.

```cpp
SharedPtr<XmlNode> System::Xml::XmlCDataSection::CloneNode(bool deep) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true** a megadott csomópont alatti részfa rekurzív klónozásához; **false** csak a csomópont saját magának klónozásához. Mivel a CDATA csomópontoknak nincsenek gyermekei, a paraméter beállítástól függetlenül a klónozott csomópont mindig tartalmazni fogja az adat tartalmat. |

### Visszatérési érték

A klónozott csomópont.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlCDataSection](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)