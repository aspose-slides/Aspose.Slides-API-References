---
title: ReadValueChunk()
second_title: Aspose.Slides C++ API hivatkozás
description: Nagy szövegfolyamokat olvas be egy XML dokumentumba ágyazva.
type: docs
weight: 807
url: /hu/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) metódus

Nagy szövegfolyamokat olvas be egy XML dokumentumba ágyazva.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Az a karaktertömb, amely a pufferként szolgál, ahová a szövegtartalom íródik. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferen belüli eltolás, ahol a [XmlReader](../) elkezdheti másolni az eredményeket. |
| count | **int32_t** | A pufferbe másolandó karakterek maximális száma. A ténylegesen másolt karakterek száma a metódus visszatérési értéke. |

### Visszatérési érték

A pufferbe beolvasott karakterek száma. Ha nincs több szövegtartalom, akkor a visszatérési érték nulla.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)