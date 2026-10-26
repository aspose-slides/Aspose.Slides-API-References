---
title: CloneNode()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehozza ennek a csomópontnak a másolatát.
type: docs
weight: 92
url: /hu/system.xml/xmlentityreference/clonenode/
---
## XmlEntityReference::CloneNode(bool) metódus

Létrehozza ennek a csomópontnak a másolatát.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntityReference::CloneNode(bool deep) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| deep | **bool** | **true** a megadott csomópont alatti részfa rekurzív klónozásához; **false** csak a csomópont önmagának klónozásához. A [XmlEntityReference](../) csomópontok esetén ez a metódus mindig egy olyan entitásreferencia csomópontot ad vissza, amelynek nincsenek gyermekei. A helyettesítő szöveg akkor kerül beállításra, amikor a csomópont szülőbe van beszúrva. |

### Visszatérési érték

A klónozott csomópont.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [XmlEntityReference](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)