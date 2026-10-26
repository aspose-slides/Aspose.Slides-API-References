---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides C++ API-referencia
description: Beolvassa az elemet és dekódolja a Base64 tartalmat.
type: docs
weight: 586
url: /hu/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus

Beolvassa az elemet és dekódolja a Base64 tartalmat.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A puffer, amelybe a visszakapott szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferben a másolás kezdőpozíciója. |
| count | **int32_t** | A pufferbe másolandó bájtok maximális száma. A ténylegesen másolt bájtok számát a metódus adja vissza. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlValidatingReader](../)
* Névtere [System::Xml](../../)
* Library [Aspose.Slides](../../../)