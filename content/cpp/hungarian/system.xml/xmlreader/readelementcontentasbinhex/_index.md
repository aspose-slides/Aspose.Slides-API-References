---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa az elemet és dekódolja a BinHex tartalmat.
type: docs
weight: 794
url: /hu/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Beolvassa az elemet, és dekódolja a **BinHex** tartalmat.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffer, amelybe a kapott szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferben a hely, ahol a másolás megkezdődik. |
| count | **int32_t** | A pufferbe másolható bájtok maximális száma. A ténylegesen másolt bájtok száma a metódus visszatérési értéke. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)