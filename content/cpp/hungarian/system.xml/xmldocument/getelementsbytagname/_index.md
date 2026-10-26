---
title: GetElementsByTagName()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaad egy XmlNodeList objektumot, amely a megadott névnek megfelelő összes leszármazott elemet tartalmazza.
type: docs
weight: 443
url: /hu/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) metódus

Visszaad egy [XmlNodeList](../../xmlnodelist/) objektumot, amely a megadott névnek megfelelő összes leszármazott elemet tartalmazza.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | A keresendő kvalifikált név. A megfelelő csomópont **get_Name** értékével hasonlítják össze. A speciális érték **\"*\"** minden címkét egyezővé tesz. |

### Visszatérési érték

Egy [XmlNodeList](../../xmlnodelist/) objektumot, amely az összes egyező csomópontot tartalmazza. Ha egy csomópont sem egyezik a **name**-vel, akkor a visszaadott gyűjtemény üres lesz.

## XmlDocument::GetElementsByTagName(String, String) metódus

Visszaad egy [XmlNodeList](../../xmlnodelist/) objektumot, amely a megadott [XmlDocument::get_LocalName](../get_localname/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/)-nek megfelelő összes leszármazott elemet tartalmazza.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A keresendő LocalName. A speciális érték **\"*\"** minden címkét egyezővé tesz. |
| namespaceURI | [String](../../../system/string/) | A keresendő NamespaceURI. |

### Visszatérési érték

Egy [XmlNodeList](../../xmlnodelist/) objektumot, amely az összes egyező csomópontot tartalmazza. Ha egy csomópont sem egyezik a megadott **localName** és **namespaceURI** értékekkel, a visszaadott gyűjtemény üres lesz.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNodeList](../../xmlnodelist/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)