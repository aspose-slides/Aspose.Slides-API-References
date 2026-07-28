---
title: ReadContentAsBase64()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa a tartalmat, és visszaadja a Base64 dekódolt bináris bájtokat.
type: docs
weight: 755
url: /hu/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Olvassa be a tartalmat, és visszaadja a Base64 dekódolt bináris bájtokat.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffert, amelybe a keletkezett szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | Az eltolás a pufferen belül, ahol a másolást el kell kezdeni. |
| count | **int32_t** | A maximális bájtok száma, amit a puffert mind be kell másolni. A ténylegesen másolt bájtok számát a metódus adja vissza. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)