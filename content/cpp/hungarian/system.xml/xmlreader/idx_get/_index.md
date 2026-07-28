---
title: idx_get()
second_title: Aspose.Slides for C++ API Referenciája
description: Amikor felülírják egy leszármazott osztályban, lekérdezi a megadott indexű attribútum értékét.
type: docs
weight: 612
url: /hu/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) metódus


Amikor felülírják egy leszármazott osztályban, lekérdezi a megadott indexű attribútum értékét.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. |

### Visszatérési érték

A megadott attribútum értéke.

## XmlReader::idx_get(String) metódus


Amikor felülírják egy leszármazott osztályban, lekérdezi a megadott [XmlReader::get_Name](../get_name/) értékű attribútum értékét.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum teljes neve. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra.

## XmlReader::idx_get(String, String) metódus


Amikor felülírják egy leszármazott osztályban, lekérdezi a megadott [XmlReader::get_LocalName](../get_localname/) és [XmlReader::get_NamespaceURI](../get_namespaceuri/) értékekkel rendelkező attribútum értékét.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-je. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)