---
title: ReadContentAsBinHex()
second_title: Aspose.Slides C++ API hivatkozás
description: Beolvassa a tartalmat, és visszaadja a BinHex-dekódolt bináris bájtokat.
type: docs
weight: 456
url: /hu/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Olvassa be a tartalmat, és visszaadja a BinHex dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A puffer, amelybe a kapott szöveget másolja. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | Az eltolás a pufferben, ahonnan a másolást megkezdi. |
| count | **int32_t** | A maximális bájtok száma, amelyet a pufferbe másol. A ténylegesen másolt bájtok száma a metódus visszatérési értéke. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlNodeReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)