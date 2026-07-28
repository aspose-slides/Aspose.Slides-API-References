---
title: ReadContentAsBinHex()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa a tartalmat, és visszaadja a BinHex dekódolt bináris bájtokat.
type: docs
weight: 664
url: /hu/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus

Beolvassa a tartalmat, és visszaadja a **BinHex** dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A puffer, amelybe a keletkezett szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | Az eltolás a pufferben, ahol a másolatot el kell kezdeni. |
| count | **int32_t** | A pufferbe másolandó bájtok maximális száma. A ténylegesen átmásolt bájtok száma a metódus visszatérési értéke. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Library [Aspose.Slides](../../../)