---
title: ToBase64CharArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Base-64 codeert een bereik van elementen in de opgegeven byte-array en slaat de gecodeerde data op als een array van Unicode-tekens.
type: docs
weight: 27
url: /nl/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) methode


Base-64 codeert een bereik van elementen in de opgegeven byte-array en slaat de gecodeerde gegevens op als een array van Unicode-tekens.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | De array met bytes die het te coderen bereik van elementen bevat |
| offset_in | int | Een index van een element in de invoer-array waarop het te coderen bereik begint |
| length | int | De lengte van het te coderen bereik van elementen |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Een constante referentie naar de uitvoer-array waarin de resulterende gegevens moeten worden geplaatst |
| offset_out | int | Een index in de uitvoer-array waarop de resulterende gegevens moeten worden geplaatst |
| insert_line_breaks | **bool** | Geeft aan of de regeleinde-tekens moeten worden ingevoegd in de uitvoer-array na elke 76 base-64-tekens |

### Retourwaarde

Het aantal tekens dat naar de uitvoer-array is geschreven

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) methode


Base-64 codeert een bereik van elementen in de opgegeven byte-array en slaat de gecodeerde gegevens op als een array van Unicode-tekens.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | De array met bytes die het te coderen bereik van elementen bevat |
| offset_in | int | Een index van een element in de invoer-array waarop het te coderen bereik begint |
| length | int | De lengte van het te coderen bereik van elementen |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Een constante referentie naar de uitvoer-array waarin de resulterende gegevens moeten worden geplaatst |
| offset_out | int | Een index in de uitvoer-array waarop de resulterende gegevens moeten worden geplaatst |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Geeft de opmaakopties van de base-64-gecodeerde gegevens aan |

### Retourwaarde

Het aantal tekens dat naar de uitvoer-array is geschreven

## Zie ook

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)