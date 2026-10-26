---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API Referencia
description: "Visszaad egy XmlNodeList, amely a megadott XmlElement::get_Name értéknek megfelelő összes leszármazott elemet tartalmazó listát."
type: docs
weight: 287
url: /hu/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) metódus

Visszaad egy [XmlNodeList](../../xmlnodelist/) amely a megadott [XmlElement::get_Name](../get_name/)-nek megfelelő összes leszármazott elem listáját tartalmazza.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A névtag, amelyet egyezni kell. Ez egy minősített név. A **get_Name** értékhez van egyeztetve a megfelelő csomópontra. A csillag (*) egy speciális érték, amely minden címkére illeszkedik. |

### Visszatérési érték

Egy [XmlNodeList](../../xmlnodelist/) amely a megfelelő csomópontok listáját tartalmazza. A lista üres, ha nincs megfelelő csomópont.

## XmlElement::GetElementsByTagName(String, String) metódus

Visszaad egy [XmlNodeList](../../xmlnodelist/) amely a megadott [XmlElement::get_LocalName](../get_localname/) és [XmlElement::get_NamespaceURI](../get_namespaceuri/) értékeknek megfelelő összes leszármazott elem listáját tartalmazza.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A helyi név, amelyet egyezni kell. A csillag (*) egy speciális érték, amely minden címkére illeszkedik. |
| namespaceURI | [String](../../../system/string/) | A névtér URI, amelyet egyezni kell. |

### Visszatérési érték

Egy [XmlNodeList](../../xmlnodelist/) amely a megfelelő csomópontok listáját tartalmazza. A lista üres, ha nincs megfelelő csomópont.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNodeList](../../xmlnodelist/)
* Osztály [String](../../../system/string/)
* Osztály [XmlElement](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)