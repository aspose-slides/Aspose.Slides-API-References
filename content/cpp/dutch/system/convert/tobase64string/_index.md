---
title: ToBase64String()
second_title: Aspose.Slides voor C++ API-referentie
description: Base-64 codeert elementen in de opgegeven byte-array en geeft de gecodeerde gegevens terug als een tekenreeks.
type: docs
weight: 40
url: /nl/system/convert/tobase64string/
---
## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, bool) methode


Base-64 codeert elementen in de opgegeven byte-array en geeft de gecodeerde gegevens terug als een tekenreeks.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, bool insert_line_breaks=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | De array van bytes om te coderen |
| insert_line_breaks | **bool** | Geeft aan of regeleindetekens moeten worden ingevoegd in de uitvoertekenreeks na elke 76 base-64 tekens |

### Retourwaarde

De tekenreeks die de base-64 gecodeerde weergave van de invoer-array bevat

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, bool) methode


Base-64 codeert een reeks elementen in de opgegeven byte-array en geeft de gecodeerde gegevens terug als een tekenreeks.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, bool insert_line_breaks=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | De array van bytes die de reeks te coderen elementen bevat |
| offset_in | int | Een index van een element in de invoer-array waarop de te coderen reeks begint |
| length | int | De lengte van de reeks te coderen elementen |
| insert_line_breaks | **bool** | Geeft aan of regeleindetekens moeten worden ingevoegd in de uitvoertekenreeks na elke 76 base-64 tekens |

### Retourwaarde

De tekenreeks die de base-64 gecodeerde weergave van de reeks elementen van de invoer-array bevat

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, Base64FormattingOptions) methode


Base-64 codeert elementen in de opgegeven byte-array en geeft de gecodeerde gegevens terug als een tekenreeks.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, Base64FormattingOptions options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | De array van bytes om te coderen |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Geeft de opmaakopties van de base-64 gecodeerde gegevens aan |

### Retourwaarde

De tekenreeks die de base-64 gecodeerde weergave van de invoer-array bevat

## Convert::ToBase64String(const ArrayPtr\<uint8_t\>\&, int, int, Base64FormattingOptions) methode


Base-64 codeert een reeks elementen in de opgegeven byte-array en geeft de gecodeerde gegevens terug als een tekenreeks.

```cpp
static String System::Convert::ToBase64String(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, Base64FormattingOptions options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | De array van bytes die de reeks te coderen elementen bevat |
| offset_in | int | Een index van een element in de invoer-array waarop de te coderen reeks begint |
| length | int | De lengte van de reeks te coderen elementen |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Geeft de opmaakopties van de base-64 gecodeerde gegevens aan |

### Retourwaarde

De tekenreeks die de base-64 gecodeerde weergave van de reeks elementen van de invoer-array bevat

## Zie ook

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)