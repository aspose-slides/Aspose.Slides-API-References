---
title: ReadContentAsBinHex()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud en retourneert de BinHex gedecodeerde binaire bytes.
type: docs
weight: 664
url: /nl/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Leest de inhoud en retourneert de **BinHex** gedecodeerde binaire bytes.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarin de resulterende tekst moet worden gekopieerd. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waar het resultaat gekopieerd moet worden. |
| count | **int32_t** | Het maximale aantal bytes dat naar de buffer gekopieerd mag worden. Het werkelijke aantal gekopieerde bytes wordt door deze methode geretourneerd. |

### Retourwaarde

Het aantal bytes dat naar de buffer is geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlTextReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)