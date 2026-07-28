---
title: GetAttribute()
second_title: Aspose.Slides for C++ API hivatkozás
description: "Ha egy származtatott osztályban felülírják, visszaadja a megadott XmlReader::get_Name értékű attribútum értékét."
type: docs
weight: 599
url: /hu/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) metódus

Ha felülírják egy származtatott osztályban, visszaadja a megadott [XmlReader::get_Name](../get_name/) értékű attribútum értékét.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum minősített neve. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, vagy az érték [String::Empty](../../../system/string/empty/), **nullptr** kerül visszaadásra.

## XmlReader::GetAttribute(String, String) metódus

Ha felülírják egy származtatott osztályban, visszaadja a megadott [XmlReader::get_LocalName](../get_localname/) és [XmlReader::get_NamespaceURI](../get_namespaceuri/) értékű attribútum értékét.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér-URI-ja. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, vagy az érték [String::Empty](../../../system/string/empty/), **nullptr** kerül visszaadásra. Ez a metódus nem mozdítja a olvasót.

## XmlReader::GetAttribute(int32_t) metódus

Ha felülírják egy származtatott osztályban, visszaadja a megadott indexű attribútum értékét.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. Az index nullával indul. (Az első attribútum indexe 0.) |

### Visszatérési érték

A megadott attribútum értéke. Ez a metódus nem mozdítja a olvasót.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)