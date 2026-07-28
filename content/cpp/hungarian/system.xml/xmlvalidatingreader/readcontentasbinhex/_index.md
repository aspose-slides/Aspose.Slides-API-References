---
title: ReadContentAsBinHex()
second_title: Aspose.Slides C++ API referenciája
description: Beolvassa a tartalmat, és visszaadja a BinHex által dekódolt bináris bájtokat.
type: docs
weight: 599
url: /hu/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Beolvassa a tartalmat, és visszaadja a BinHex által dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A puffer, amelybe a létrejött szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | Az eltolás a pufferben, ahol a másolás elkezdődik. |
| count | **int32_t** | A pufferbe másolandó bájtok maximális száma. A ténylegesen átmásolt bájtok száma a metódus visszatérési értéke. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlValidatingReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)