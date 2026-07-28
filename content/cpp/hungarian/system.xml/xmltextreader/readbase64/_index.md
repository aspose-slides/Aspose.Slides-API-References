---
title: ReadBase64()
second_title: Aspose.Slides C++ API referencia
description: Dekódolja a Base64-et és visszaadja a dekódolt bináris bájtokat.
type: docs
weight: 768
url: /hu/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metódus

Dekódolja a Base64-et, és visszaadja a dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | A karakterek tömbje, amely a puffert szolgálja, ahová a szöveg tartalma íródik. |
| offset | **int32_t** | A nullától kezdődő index a tömbben, amely megadja, hol kezdheti a metódus a pufferbe írást. |
| len | **int32_t** | A pufferbe írandó bájtok száma. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)