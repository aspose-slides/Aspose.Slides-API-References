---
title: ReadContentAsBase64()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přečte obsah a vrátí binární bajty dekódované z Base64.
type: docs
weight: 755
url: /cs/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metoda


Přečte obsah a vrátí binární bajty dekódované z Base64.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
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
* Třída [XmlReader](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)