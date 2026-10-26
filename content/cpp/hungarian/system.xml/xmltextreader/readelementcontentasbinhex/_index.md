---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API hivatkozás
description: Beolvassa az elemet, és dekódolja a BinHex tartalmat.
type: docs
weight: 677
url: /hu/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Beolvassa az elemet, és dekódolja a **BinHex** tartalmat.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffer, amelybe a keletkezett szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferben a másolás kezdőpontja. |
| count | **int32_t** | A maximális bájtszám, amelyet a pufferbe másolni kell. A ténylegesen másolt bájtok száma a metódus visszatérési értéke. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)