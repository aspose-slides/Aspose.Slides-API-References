---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides pro C++ API Reference
description: Načte prvek a dekóduje obsah BinHex.
type: docs
weight: 482
url: /cs/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda

Načte prvek a dekóduje obsah BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer, do kterého se kopíruje výsledný text. Tato hodnota nemůže být **nullptr**. |
| index | **int32_t** | Posun v bufferu, kde začít kopírovat výsledek. |
| count | **int32_t** | Maximální počet bajtů, které se mají zkopírovat do bufferu. Skutečný počet zkopírovaných bajtů je vrácen z této metody. |

### Návratová hodnota

Počet bajtů zapsaných do bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)