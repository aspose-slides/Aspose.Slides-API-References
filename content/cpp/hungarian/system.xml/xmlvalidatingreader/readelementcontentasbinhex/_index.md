---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa az elemet és dekódolja a BinHex tartalmat.
type: docs
weight: 612
url: /hu/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus

Beolvassa az elemet és dekódolja a BinHex tartalmat.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A puffer, amelybe a keletkezett szöveget másolják. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferben a kezdőeltolás, ahonnan a másolás elkezdődik. |
| count | **int32_t** | A pufferbe másolható bájtok maximális száma. A valójában másolt bájtok száma ezzel a metódussal kerül visszaadásra. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlValidatingReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)