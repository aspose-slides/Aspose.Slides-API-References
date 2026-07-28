---
title: ReadContentAsBinHex()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa a tartalmat, és visszaadja a BinHex dekódolt bináris bájtokat.
type: docs
weight: 781
url: /hu/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Olvassa be a tartalmat, és visszaadja a **BinHex** dekódolt bináris bájtokat.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffer, amelybe a resultáló szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | Az eltolás a pufferben, ahol a másolást meg kell kezdeni. |
| count | **int32_t** | A maximális bájtszám, amelyet a pufferbe másolni kell. A ténylegesen másolt bájtok száma visszatér ezzel a metódussal. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlReader](../)
* Névtér [System::Xml](../../)
* Library [Aspose.Slides](../../../)