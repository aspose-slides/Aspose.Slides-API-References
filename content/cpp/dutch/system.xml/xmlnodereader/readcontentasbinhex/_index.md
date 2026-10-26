---
title: ReadContentAsBinHex()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud en retourneert de BinHex-gedecodeerde binaire bytes.
type: docs
weight: 456
url: /nl/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Leest de inhoud en retourneert de BinHex-gedecodeerde binaire bytes.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De buffer waarin de resulterende tekst wordt gekopieerd. Deze waarde mag niet **nullptr** zijn. |
| index | **int32_t** | De offset in de buffer waar het kopiëren van het resultaat moet beginnen. |
| count | **int32_t** | Het maximale aantal bytes dat naar de buffer gekopieerd moet worden. Het daadwerkelijke aantal gekopieerde bytes wordt door deze methode geretourneerd. |

### Retourwaarde

Het aantal bytes geschreven naar de buffer.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [XmlNodeReader](../)
* Naamruimte [System::Xml](../../)
* Library [Aspose.Slides](../../../)