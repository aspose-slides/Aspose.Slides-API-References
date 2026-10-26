---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest het element en decodeert de Base64-inhoud.
type: docs
weight: 651
url: /nl/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Leest het element en decodeert de Base64-inhoud.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarin de resulterende tekst gekopieerd moet worden. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waar het resultaat gekopieerd moet worden. |
| count | **int32_t** | Het maximum aantal bytes dat naar de buffer gekopieerd moet worden. Het werkelijke aantal gekopieerde bytes wordt door deze methode geretourneerd. |

### Retourwaarde

Het aantal bytes dat naar de buffer is geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlTextReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)