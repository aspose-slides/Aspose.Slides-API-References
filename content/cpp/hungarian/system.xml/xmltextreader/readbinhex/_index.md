---
title: ReadBinHex()
second_title: Aspose.Slides for C++ API Referenciája
description: Dekódolja a BinHex-et és visszaadja a dekódolt bináris bájtokat.
type: docs
weight: 781
url: /hu/system.xml/xmltextreader/readbinhex/
---
## XmlTextReader::ReadBinHex(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus


Dekódolja a **BinHex**-et, és visszaadja a dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlTextReader::ReadBinHex(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A bájt tömb, amely a puffert képezi, ahová a dekódolt bináris bájtok íródnak. |
| offset | **int32_t** | A tömbben a nullától induló index, amely megadja, hol kezdhet a metódus a puffert írni. |
| len | **int32_t** | A pufferekbe írandó bájtok száma. |

### Visszatérési érték

A pufferrbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)