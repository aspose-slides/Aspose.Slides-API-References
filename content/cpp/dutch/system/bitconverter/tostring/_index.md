---
title: ToString()
second_title: Aspose.Slides voor C++ API Referentie
description: Converteert alle waarden van de opgegeven byte-array naar hun hexadecimale tekenreeksrepresentatie. Hoofdlettergebruik voor letters in de hexadecimale notatie en het scheidingsteken dat tussen elk paar aangrenzende bytes wordt ingevoegd, worden gespecificeerd via de overeenkomstige argumenten.
type: docs
weight: 157
url: /nl/system/bitconverter/tostring/
---
## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, bool, const String\&) methode


Converteert alle waarden van de opgegeven byte-array naar hun hexadecimale tekenreeksrepresentatie. Hoofdlettergebruik voor letters in de hexadecimale notatie en het scheidingsteken dat tussen elke paar aangrenzende bytes wordt ingevoegd, worden gespecificeerd via de overeenkomstige argumenten.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, bool uppercase=1, const String &separator=u"-")
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| uppercase | **bool** | Specificeert het hoofdlettergebruik voor letters in de resulterende hexadecimale representatie |
| separator | const [String](../../string/)\& | Een tekenreeks die als scheidingsteken wordt ingevoegd tussen elk paar aangrenzende bytes in de resulterende tekenreeks |

### Retourwaarde

[String](../../string/) die de hexadecimale representatie van de opgegeven byte-array bevat

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int) methode


Converteert waarden van de opgegeven byte-array naar hun hexadecimale tekenreeksrepresentatie, beginnend bij de opgegeven index.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de opgegeven array waarop de conversie moet beginnen |

### Retourwaarde

[String](../../string/) die de hexadecimale representatie van het opgegeven bereik van elementen van de opgegeven array bevat

## BitConverter::ToString(const ArrayPtr\<uint8_t\>\&, int, int) methode


Converteert een reeks waarden van de opgegeven byte-array naar hun hexadecimale tekenreeksrepresentatie.

```cpp
static String System::BitConverter::ToString(const ArrayPtr<uint8_t> &value, int startIndex, int length)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de opgegeven array waarop het bereik van de te converteren byte-array-elementen begint |
| length | int | De lengte van het bereik van de te converteren elementen van de byte-array |

### Retourwaarde

[String](../../string/) die de hexadecimale representatie van het opgegeven bereik van elementen van de opgegeven array bevat

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [String](../../string/)
* Klasse [BitConverter](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)