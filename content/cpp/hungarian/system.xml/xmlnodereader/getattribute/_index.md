---
title: GetAttribute()
second_title: Aspose.Slides for C++ API Referencia
description: Visszaadja a megadott névvel rendelkező attribútum értékét.
type: docs
weight: 287
url: /hu/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) metódus


Visszaadja a megadott névvel rendelkező attribútum értékét.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum kvalifikált neve. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra.

## XmlNodeReader::GetAttribute(String, String) metódus


Visszaadja a megadott helyi névvel és névtér-URI-vel rendelkező attribútum értékét.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | Az attribútum helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az attribútum névtér-URI-ja. |

### Visszatérési érték

A megadott attribútum értéke. Ha az attribútum nem található, **nullptr** kerül visszaadásra.

## XmlNodeReader::GetAttribute(int32_t) metódus


Visszaadja a megadott indexű attribútum értékét.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| attributeIndex | **int32_t** | Az attribútum indexe. Az index nullától kezdődik. (Az első attribútum indexe 0.) |

### Visszatérési érték

A megadott attribútum értéke.

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [XmlNodeReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)