---
title: get_ParentNode()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja ennek a csomópontnak a szülőjét (azokra a csomópontokra, amelyeknek lehet szülőjük).
type: docs
weight: 53
url: /hu/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() metódus


Visszaadja ennek a csomópontnak a szülőjét (azokra a csomópontokra, amelyeknek lehet szülőjük).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```


### Return Value

A [XmlNode](../), amely az aktuális csomópont szülője.

## Megjegyzések



Ha egy csomópontot éppen most hoztak létre, és még nem került be a fába, vagy ha a fából eltávolították, a szülő **nullptr**. Minden más csomópont esetén a visszaadott érték a csomópont [XmlNode::get_NodeType](../get_nodetype/)-től függ. Az alábbi táblázat leírja a **get_NodeType** metódus lehetséges visszatérési értékeit. 

| NodeType | ParentNode visszatérési értéke |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Visszaadja a `nullptr`-t; ezek a csomópontoknak nincs szülőjük. |
| CDATA | Visszaadja azt az elemet vagy entitás hivatkozást, amely a CDATA szekciót tartalmazza. |
| Comment | Visszaadja azt az elemet, entitás hivatkozást, dokumentumtípust vagy dokumentumot, amely a megjegyzést tartalmazza. |
| DocumentType | Visszaadja a dokumentum csomópontot. |
| Element | Visszaadja az elem szülő csomópontját. Ha az elem a fa gyökércsomópontja, a szülő a dokumentum csomópont. |
| EntityReference | Visszaadja azt az elemet, attribútumot vagy entitás hivatkozást, amely az entitás hivatkozást tartalmazza. |
| ProcessingInstruction | Visszaadja azt a dokumentumot, elemet, dokumentumtípust vagy entitás hivatkozást, amely a feldolgozási utasítást tartalmazza. |
| [Text](../../../system.text/)| Visszaadja a szülő elemet, attribútumot vagy entitás hivatkozást, amely a szöveg csomópontot tartalmazza. |


## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)