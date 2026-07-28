---
title: ReadElementContentAsObject()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa az aktuális elemet, és visszaadja a tartalmat Objectként.
type: docs
weight: 469
url: /hu/system.xml/xmlreader/readelementcontentasobject/
---
## XmlReader::ReadElementContentAsObject() metódus


Olvassa be az aktuális elemet, és visszaadja a tartalmat mint egy [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject()
```


### Visszatérési érték

Egy legmegfelelőbb típusú dobozolt objektum. A [XmlReader::get_ValueType](../get_valuetype/) érték határozza meg a megfelelő típust. Ha a tartalom listatípusú, akkor ez a metódus a megfelelő típusú dobozolt objektumok tömbjét adja vissza.

## XmlReader::ReadElementContentAsObject(String, String) metódus


Ellenőrzi, hogy a megadott helyi név és névtér URI egyezik-e az aktuális elemével, majd beolvassa az aktuális elemet, és visszaadja a tartalmat mint egy [Object](../../../system/object/).

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAsObject(String localName, String namespaceURI)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Az elem helyi neve. |
| namespaceURI | [String](../../../system/string/) | Az elem névtér URI-ja. |

### Visszatérési érték

Egy legmegfelelőbb típusú dobozolt objektum. A [XmlReader::get_ValueType](../get_valuetype/) érték határozza meg a megfelelő típust. Ha a tartalom listatípusú, akkor ez a metódus a megfelelő típusú dobozolt objektumok tömbjét adja vissza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [XmlReader](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)