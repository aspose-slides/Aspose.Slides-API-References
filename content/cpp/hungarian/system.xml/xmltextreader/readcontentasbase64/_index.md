---
title: ReadContentAsBase64()
second_title: Aspose.Slides C++ API referencia
description: Beolvassa a tartalmat, és visszaadja a Base64 dekódolt bináris bájtokat.
type: docs
weight: 638
url: /hu/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) módszer


Olvassa be a tartalmat, és visszaadja a **Base64** dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffer, amelybe a keletkezett szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferen lévő eltolás, ahol a másolás a eredménnyel kezdődik. |
| count | **int32_t** | A maximális bájtok száma, amelyet a pufferbe másolni kell. A ténylegesen átmásolt bájtok száma ezzel a módszerrel kerül visszaadásra. |

## Visszatérési érték

A pufferbe írt bájtok száma.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlTextReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)