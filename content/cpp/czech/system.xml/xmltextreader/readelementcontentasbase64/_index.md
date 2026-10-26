---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides pro C++ API Reference
description: Načte prvek a dekóduje obsah ve formátu Base64.
type: docs
weight: 651
url: /cs/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda

Načte prvek a dekóduje obsah ve formátu Base64.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Vyrovnávací paměť, do které se má zkopírovat výsledný text. Tato hodnota nesmí být **nullptr**. |
| index | **int32_t** | Posun ve vyrovnávací paměti, odkud se má začít kopírovat výsledek. |
| count | **int32_t** | Maximální počet bajtů, které mají být zkopírovány do vyrovnávací paměti. Skutečný počet zkopírovaných bajtů je vrácen touto metodou. |

### Návratová hodnota

Počet bajtů zapsaných do vyrovnávací paměti.

## Viz také

* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)