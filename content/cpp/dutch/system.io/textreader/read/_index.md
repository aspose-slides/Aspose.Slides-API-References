---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest een enkel teken uit de stream.
type: docs
weight: 40
url: /nl/system.io/textreader/read/
---
## TextReader::Read() methode


Leest een enkel teken uit de stream.

```cpp
virtual int System::IO::TextReader::Read()
```


### Retourwaarde

Leest teken gecodeerd met UTF-16-codering; indien het gelezen teken wordt gerepresenteerd door twee codepunten in UTF-16-codering, wordt alleen de hoge surrogaat geretourneerd.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) methode


Leest het opgegeven aantal tekens uit de stream en schrijft ze naar het opgegeven tekenarray beginnend op de opgegeven positie.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | De UTF-16 tekenarray om de uit de stream gelezen tekens naar toe te schrijven |
| index | int | Een op 0 beginnende index in **buffer** waarop het schrijven moet beginnen |
| count | int | Het aantal tekens dat gelezen moet worden uit de stream |

### Retourwaarde

Het aantal tekens dat uit de stream is gelezen

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [TextReader](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)