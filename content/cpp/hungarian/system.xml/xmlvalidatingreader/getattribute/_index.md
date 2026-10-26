---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Referenciája
description: Visszaadja a megadott névvel rendelkező attribútum értékét.
type: docs
weight: 443
url: /hu/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) metódus

Visszaadja a megadott névvel rendelkező attribútum értékét.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum minősített neve. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra.

## XmlValidatingReader::GetAttribute(String, String) metódus

Visszaadja a megadott helyi névvel és névtér Uniform Resource Identifier (URI)-vel rendelkező attribútum értékét.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér URI-ja. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra. Ez a metódus nem mozdítja a olvasót.

## XmlValidatingReader::GetAttribute(int32_t) metódus

Visszaadja a megadott indexű attribútum értékét.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. Az index nullártól indul. (Az első attribútumnak 0 a indexe.) |

### Visszatérési érték

A megadott attribútum értéke.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlValidatingReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)