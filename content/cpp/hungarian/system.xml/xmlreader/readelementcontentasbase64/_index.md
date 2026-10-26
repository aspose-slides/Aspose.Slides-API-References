---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides C++ API referenciája
description: Beolvassa az elemet és dekódolja a Base64 tartalmat.
type: docs
weight: 768
url: /hu/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


A elemet olvassa és dekódolja a **Base64** tartalmat.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffer, amelybe a kapott szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | Az eltolás a pufferen belül, ahol a másolást el kell kezdeni. |
| count | **int32_t** | A pufferbe másolandó bájtok maximális száma. A ténylegesen másolt bájtok számát ez a metódus adja vissza. |

### Visszatérési érték

A puffert írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)