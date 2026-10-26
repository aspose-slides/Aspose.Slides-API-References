---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API referencia
description: Beolvassa az elemet, és dekódolja a Base64 tartalmat.
type: docs
weight: 469
url: /hu/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Olvassa be az elemet, és dekódolja a Base64 tartalmat.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A buffer, amelybe a kapott szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A buffer eltolása, ahol a másolást elkezdi. |
| count | **int32_t** | A maximális byteok száma, amelyet a bufferbe másolni kell. A ténylegesen másolt byteok száma ebből a metódusból kerül visszaadva. |

### Visszatérési érték

A bufferbe írt byteok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlNodeReader](../)
* Névtere [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)