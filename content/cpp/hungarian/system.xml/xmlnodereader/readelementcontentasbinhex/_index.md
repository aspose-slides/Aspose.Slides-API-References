---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides C++ API referenciája
description: Beolvassa az elemet, és dekódolja a BinHex tartalmat.
type: docs
weight: 482
url: /hu/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metódus


Elolvassa az elemet, és dekódolja a BinHex tartalmat.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Az a puffert, amelybe a kapott szöveget másolni kell. Ez az érték nem lehet **nullptr**. |
| index | **int32_t** | A puffertől számított eltolás, ahonnan a másolást el kell kezdeni. |
| count | **int32_t** | A maximális számú bájt, amelyet a puffervébe másolni kell. A ténylegesen másolt bájtok száma a metódus visszatérési értéke. |

### Visszatérési érték

A puffertbe írt bájtok száma.

## Lásd még

* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [XmlNodeReader](../)
* Névterület [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)