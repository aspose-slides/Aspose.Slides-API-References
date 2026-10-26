---
title: Read()
second_title: Aspose.Slides voor C++ API Referentie
description: Leest een enkel teken van de stroom.
type: docs
weight: 40
url: /nl/system.io/stringreader/read/
---
## StringReader::Read() methode

Leest een enkel teken van de stroom.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Retourwaarde

Een gelezen teken of -1 als er geen teken is gelezen

## StringReader::Read(ArrayPtr\<char_t\>, int, int) methode

Leest het opgegeven aantal tekens van de stroom naar het opgegeven tekenarray beginnend op de opgegeven positie.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Het tekenarray om de van de stroom gelezen tekens naar te schrijven |
| index | int | Een 0-gebaseerde index in **buffer** waarop begonnen wordt met schrijven |
| count | int | Het aantal tekens dat van de stroom moet worden gelezen |

### Retourwaarde

Het aantal tekens dat van de stroom is gelezen

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StringReader](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)