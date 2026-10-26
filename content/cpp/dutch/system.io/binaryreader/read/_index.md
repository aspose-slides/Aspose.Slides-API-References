---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest een enkel teken van de invoerstroom.
type: docs
weight: 66
url: /nl/system.io/binaryreader/read/
---
## BinaryReader::Read() methode

Leest een enkel teken van de invoerstroom.

```cpp
virtual int System::IO::BinaryReader::Read()
```

### Retourwaarde

Leest teken gecodeerd met UTF-16-codering; als het gelezen teken wordt weergegeven door twee codepunten in UTF-16-codering, wordt alleen de hoge surrogaat geretourneerd.

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) methode

Leest het opgegeven aantal bytes van de invoerstroom en schrijft ze naar de opgegeven byte-array.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | De byte-array om de gelezen bytes naartoe te schrijven |
| index | int | Een 0-gebaseerde positie in **buffer** om te beginnen met schrijven |
| count | int | Het aantal bytes om te lezen |

### Retourwaarde

Het aantal gelezen bytes

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) methode

Leest het opgegeven aantal tekens van de invoerstroom, zet ze om naar UTF-16-codering en schrijft de resulterende UTF-16-tekens naar de opgegeven teken-array beginnend op de opgegeven positie.

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | De UTF-16-tekenarray om de gelezen tekens van de invoerstroom naartoe te schrijven |
| index | int | Een 0-gebaseerde index in **buffer** waarop begonnen wordt met schrijven |
| count | int | Het aantal tekens dat gelezen moet worden van de stroom |

### Retourwaarde

Het aantal tekens dat gelezen is van de invoerstroom

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [BinaryReader](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)