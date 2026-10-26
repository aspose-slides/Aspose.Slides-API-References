---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides pro C++ API Reference
description: Načte prvek a dekóduje obsah ve formátu Base64.
type: docs
weight: 469
url: /cs/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda

Načte prvek a dekóduje obsah ve formátu Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer, do kterého se má zkopírovat výsledný text. Tato hodnota nesmí být **nullptr**. |
| index | **int32_t** | Posun v bufferu, kde začít kopírovat výsledek. |
| count | **int32_t** | Maximální počet bytů, které se mají zkopírovat do bufferu. Skutečný počet zkopírovaných bytů je vrácen touto metodou. |

### Návratová hodnota

Počet bytů zapsaných do bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlNodeReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)