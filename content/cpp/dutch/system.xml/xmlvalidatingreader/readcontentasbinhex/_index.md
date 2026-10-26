---
title: ReadContentAsBinHex()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud en retourneert de BinHex-gedecodeerde binaire bytes.
type: docs
weight: 599
url: /nl/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) methode

Leest de inhoud en retourneert de BinHex-gedecodeerde binaire bytes.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarnaar de resulterende tekst gekopieerd moet worden. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waar het resultaat gekopieerd moet worden. |
| count | **int32_t** | Het maximum aantal bytes dat naar de buffer gekopieerd moet worden. Het daadwerkelijke aantal gekopieerde bytes wordt geretourneerd door deze methode. |

### Retourwaarde

Het aantal bytes dat naar de buffer is geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlValidatingReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)