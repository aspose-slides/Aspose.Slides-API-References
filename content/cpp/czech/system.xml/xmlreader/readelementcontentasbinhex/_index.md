---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides pro C++ API Reference
description: Načte prvek a dekóduje obsah BinHex.
type: docs
weight: 794
url: /cs/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda

Načte prvek a dekóduje obsah **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer, do kterého se má zkopírovat výsledný text. Tato hodnota nesmí být **nullptr**. |
| index | **int32_t** | Posun v bufferu, kde se má začít kopírovat výsledek. |
| count | **int32_t** | Maximální počet bajtů, které se mají zkopírovat do bufferu. Skutečný počet zkopírovaných bajtů je vrácen touto metodou. |

### Návratová hodnota

Počet bajtů zapsaných do bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)