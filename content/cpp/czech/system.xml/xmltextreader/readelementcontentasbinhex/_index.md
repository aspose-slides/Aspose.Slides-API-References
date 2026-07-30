---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Načte prvek a dekóduje obsah BinHex.
type: docs
weight: 677
url: /cs/system.xml/xmltextreader/readelementcontentasbinhex/
---
## XmlTextReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda


Načte element a dekóduje obsah **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer, do kterého se má zkopírovat výsledný text. Tato hodnota nemůže být **nullptr**. |
| index | **int32_t** | Posun v bufferu, odkud začít kopírovat výsledek. |
| count | **int32_t** | Maximální počet bajtů, které se mají zkopírovat do bufferu. Skutečný počet zkopírovaných bajtů je vrácen touto metodou. |

### Návratová hodnota

Počet bajtů zapsaných do bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)