---
title: ToChar()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert twee bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een char_t waarde.
type: docs
weight: 40
url: /nl/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) method

Converteert twee bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een char_t-waarde.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop het opnemen van bytes voor conversie moet beginnen |

### Retourwaarde

char_t-waarde die resulteert uit de conversie

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) method

Converteert twee bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een char_t-waarde.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop het opnemen van bytes voor conversie moet beginnen |

### Retourwaarde

char_t-waarde die resulteert uit de conversie

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)