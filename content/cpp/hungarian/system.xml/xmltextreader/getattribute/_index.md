---
title: GetAttribute()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott névvel rendelkező attribútum értékét.
type: docs
weight: 495
url: /hu/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) metódus

Visszaadja a megadott névvel rendelkező attribútum értékét.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum minősített neve. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra.

## XmlTextReader::GetAttribute(String, String) metódus

Visszaadja a megadott helyi névvel és névtér-URI-vel rendelkező attribútum értékét.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér-URI-ja. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra. Ez a metódus nem mozgatja az olvasót.

## XmlTextReader::GetAttribute(int32_t) metódus

Visszaadja a megadott indexű attribútum értékét.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| i | **int32_t** | Az attribútum indexe. Az index nullától kezdődik. (Az első attribútum indexe 0.) |

### Visszatérési érték

A megadott attribútum értéke.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)