---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het element en decodeert de BinHex-inhoud.
type: docs
weight: 612
url: /nl/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) methode

Leest het element en decodeert de BinHex-inhoud.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarin de resulterende tekst gekopieerd moet worden. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waar het resultaat gekopieerd moet worden. |
| count | **int32_t** | Het maximum aantal bytes dat in de buffer gekopieerd moet worden. Het werkelijke aantal gekopieerde bytes wordt geretourneerd door deze methode. |

### Retourwaarde

Het aantal bytes dat naar de buffer is geschreven.

## Zie Ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlValidatingReader](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)