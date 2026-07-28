---
title: IsStartElement()
second_title: Aspose.Slides for C++ API referencia
description: "Meghívja az XmlReader::MoveToContent metódust, és ellenőrzi, hogy a jelenlegi tartalomcsomópont kezdő címke vagy üres elem címke-e."
type: docs
weight: 885
url: /hu/system.xml/xmlreader/isstartelement/
---
## XmlReader::IsStartElement() method

Meghívja [XmlReader::MoveToContent](../movetocontent/) és teszteli, hogy az aktuális tartalomcsomópont egy kezdő címke vagy üres elem címke-e.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement()
```

### Visszatérési érték

**true** ha [XmlReader::MoveToContent](../movetocontent/) egy kezdő címkét vagy üres elem címkét talál; **false** ha a [XmlNodeType::Element](../../xmlnodetype/)-től eltérő csomóponttípus található.

## XmlReader::IsStartElement(String) method

Meghívja [XmlReader::MoveToContent](../movetocontent/) és teszteli, hogy az aktuális tartalomcsomópont egy kezdő címke vagy üres elem címke-e, és hogy a megtalált elem [XmlReader::get_Name](../get_name/) értéke egyezik-e a megadott argumentummal.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String name)
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A megtalált elem **Name** értékéhez illesztett karakterlánc. |

### Visszatérési érték

**true** ha a kapott csomópont egy elem, és a **Name** érték megegyezik a megadott karakterlánccal; **false** ha a [XmlNodeType::Element](../../xmlnodetype/)-től eltérő csomóponttípus található, vagy ha az elem **Name** értéke nem egyezik a megadott karakterlánccal.

## XmlReader::IsStartElement(String, String) method

Meghívja [XmlReader::MoveToContent](../movetocontent/) és teszteli, hogy az aktuális tartalomcsomópont egy kezdő címke vagy üres elem címke-e, és hogy a megtalált elem [XmlReader::get_LocalName](../get_localname/) és [XmlReader::get_NamespaceURI](../get_namespaceuri/) értékei megegyeznek-e a megadott karakterláncokkal.

```cpp
virtual bool System::Xml::XmlReader::IsStartElement(String localname, String ns)
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localname | [String](../../../system/string/) | A megtalált elem **LocalName** értékéhez illesztendő karakterlánc. |
| ns | [String](../../../system/string/) | A megtalált elem **NamespaceURI** értékéhez illesztendő karakterlánc. |

### Visszatérési érték

**true** ha a kapott csomópont egy elem. **false** ha a [XmlNodeType::Element](../../xmlnodetype/)-től eltérő csomóponttípus található, vagy ha a **LocalName** és **NamespaceURI** értékek nem egyeznek a megadott karakterláncokkal.

## Lásd még

* Osztály [XmlReader](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)