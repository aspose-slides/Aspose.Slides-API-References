---
title: ReadContentAsBase64()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud en retourneert de Base64-gedecodeerde binaire bytes.
type: docs
weight: 573
url: /nl/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) methode

Leest de inhoud en retourneert de Base64-gedecodeerde binaire bytes.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarin de resulterende tekst moet worden gekopieerd. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waarop het resultaat moet worden gekopieerd. |
| count | **int32_t** | Het maximale aantal bytes dat naar de buffer moet worden gekopieerd. Het werkelijke aantal gekopieerde bytes wordt geretourneerd door deze methode. |

### Retourwaarde

Het aantal bytes dat naar de buffer is geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlValidatingReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)