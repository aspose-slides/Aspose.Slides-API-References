---
title: idx_get()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott indexű attribútumot.
type: docs
weight: 1
url: /hu/system.xml/xmlattributecollection/idx_get/
---
## XmlAttributeCollection::idx_get(int32_t) metódus


Visszaadja a megadott indexű attribútumot.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(int32_t i)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. |

### Visszatérési érték

A megadott indexű attribútum.

## XmlAttributeCollection::idx_get(const String\&) metódus


Visszaadja a megadott névű attribútumot.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Az attribútum kvalifikált neve. |

### Visszatérési érték

A megadott névű attribútum. Ha az attribútum nem létezik, ez a metódus **nullptr** értékkel tér vissza.

## XmlAttributeCollection::idx_get(const String\&, const String\&) metódus


Visszaadja a megadott helyi névű és névtér-Uniform Resource Identifier (URI) értékű attribútumot.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::idx_get(const String &localName, const String &namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Az attribútum helyi neve. |
| namespaceURI | const [String](../../../system/string/)\& | Az attribútum névtér-URI-je. |

### Visszatérési érték

A megadott helyi névű és névtér-URI értékű attribútum. Ha az attribútum nem létezik, ez a metódus **nullptr** értékkel tér vissza.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlAttribute](../../xmlattribute/)
* Osztály [XmlAttributeCollection](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)