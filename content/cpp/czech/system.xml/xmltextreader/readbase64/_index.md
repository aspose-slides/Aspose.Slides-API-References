---
title: ReadBase64()
second_title: Aspose.Slides pro C++ API Reference
description: Dekóduje Base64 a vrací dekódované binární bajty.
type: docs
weight: 768
url: /cs/system.xml/xmltextreader/readbase64/
---
## XmlTextReader::ReadBase64(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda

Dekóduje Base64 a vrátí dekódované binární bajty.

```cpp
int32_t System::Xml::XmlTextReader::ReadBase64(const ArrayPtr<uint8_t> &array, int32_t offset, int32_t len)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole znaků, které slouží jako buffer, do kterého jsou zapisovány textové obsahy. |
| offset | **int32_t** | Nulový index do pole, který určuje, kde může metoda začít zapisovat do bufferu. |
| len | **int32_t** | Počet bajtů, které mají být zapsány do bufferu. |

### Návratová hodnota

Počet bajtů zapsaných do bufferu.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [XmlTextReader](../)
* Jmenný prostor [System::Xml](../../)
* Knihovna [Aspose.Slides](../../../)