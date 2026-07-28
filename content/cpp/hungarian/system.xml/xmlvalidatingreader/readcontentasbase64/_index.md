---
title: ReadContentAsBase64()
second_title: Aspose.Slides C++ API Referencia
description: Beolvassa a tartalmat, és visszaadja a Base64 dekódolt bináris bájtokat.
type: docs
weight: 573
url: /hu/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Beolvassa a tartalmat, és visszaadja a Base64 dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | A puffer, amelybe a kapott szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | Az eltolás a pufferben, ahol a másolást el kell kezdeni. |
| count | **int32_t** | A pufferbe másolandó bájtok maximális száma. A ténylegesen másolt bájtok száma az e metódusból kerül visszaadásra. |

### Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlValidatingReader](../)
* Névtér [System::Xml](../../)
* Library [Aspose.Slides](../../../)