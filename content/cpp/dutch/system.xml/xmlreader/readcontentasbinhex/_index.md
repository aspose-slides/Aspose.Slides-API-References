---
title: ReadContentAsBinHex()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud en retourneert de BinHex-gedecodeerde binaire bytes.
type: docs
weight: 781
url: /nl/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) methode


Leest de inhoud en retourneert de **BinHex** gedecodeerde binaire bytes.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarin de resulterende tekst moet worden gekopieerd. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waar het resultaat moet worden gekopieerd. |
| count | **int32_t** | Het maximum aantal bytes dat naar de buffer gekopieerd mag worden. Het daadwerkelijke aantal gekopieerde bytes wordt door deze methode geretourneerd. |

### Retourwaarde

Het aantal bytes dat naar de buffer is geschreven.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlReader](../)
* Naamruimte [System::Xml](../../)
* Bibliotheek [Aspose.Slides](../../../)