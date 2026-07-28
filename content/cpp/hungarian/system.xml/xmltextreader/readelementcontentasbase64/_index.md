---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API Referencia
description: Beolvassa az elemet és dekódolja a Base64 tartalmat.
type: docs
weight: 651
url: /hu/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus

Beolvassa az elemet és dekódolja a Base64 tartalmat.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffer, amelybe a kapott szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferben a másolás kezdőpozíciójának eltolása. |
| count | **int32_t** | A pufferbe másolható bájtok maximális száma. A ténylegesen másolt bájtok száma a metódusból kerül visszaadásra. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)