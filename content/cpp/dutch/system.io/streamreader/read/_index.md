---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest een enkel teken uit de stream.
type: docs
weight: 40
url: /nl/system.io/streamreader/read/
---
## StreamReader::Read() methode

Leest een enkel teken uit de stream.

```cpp
virtual int System::IO::StreamReader::Read() override
```

### Retourwaarde

Leest een teken gecodeerd met UTF-16-encoding; als het gelezen teken wordt weergegeven door twee codepoints in UTF-16-encoding, wordt alleen de hoge surragate teruggegeven.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) methode

Leest het opgegeven aantal tekens uit de stream, converteert ze naar UTF-16-encoding en schrijft de resulterende UTF-16-tekens naar de opgegeven tekenarray beginnend op de opgegeven positie.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | De UTF-16-tekenarray om de tekens die uit de stream gelezen zijn naar te schrijven |
| index | int | Een 0-gebaseerde index in **buffer** waarop het schrijven moet beginnen |
| count | int | Het aantal tekens om uit de stream te lezen |

### Retourwaarde

Het aantal tekens dat uit de stream gelezen is.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StreamReader](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)