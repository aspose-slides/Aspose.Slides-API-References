---
title: ReadContentAsBase64()
second_title: Aspose.Slides C++ API Referenciája
description: Elolvassa a tartalmat és visszaadja a Base64 dekódolt bináris bájtokat.
type: docs
weight: 443
url: /hu/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Elolvassa a tartalmat, és visszaadja a Base64 dekódolt bináris bájtokat.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffer, amelybe a keletkezett szöveget másolják. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A pufferben a másolás eredményének kezdeti eltolása. |
| count | **int32_t** | A pufferbe másolandó bájtok maximális száma. A ténylegesen átmásolt bájtok száma ebből a metódusból kerül visszaadásra. |

### Visszatérési érték

A pufferbe írt bájtok számát.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlNodeReader](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)