---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het element en decodeert de BinHex-inhoud.
type: docs
weight: 794
url: /nl/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) methode

Leest het element en decodeert de **BinHex**-inhoud.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarin de resulterende tekst moet worden gekopieerd. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waar het resultaat moet worden gekopieerd. |
| count | **int32_t** | Het maximale aantal bytes dat gekopieerd moet worden naar de buffer. Het werkelijke aantal gekopieerde bytes wordt geretourneerd door deze methode. |

### Retourwaarde

Het aantal bytes dat naar de buffer is geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)