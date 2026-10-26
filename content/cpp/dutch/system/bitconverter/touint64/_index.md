---
title: ToUInt64()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert acht bytes van de opgegeven array vanaf de opgegeven index naar een ongetekende 64-bits gehele getalwaarde.
type: docs
weight: 118
url: /nl/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) methode

Converteert acht bytes van de opgegeven array beginnend bij de opgegeven index naar een ongetekende 64-bits gehele getalwaarde.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waar begonnen moet worden met het nemen van bytes voor conversie |

### Retourwaarde

Ongetekende 64-bits gehele getalwaarde die voortkomt uit de conversie

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) methode

Converteert acht bytes van de opgegeven array beginnend bij de opgegeven index naar een ongetekende 64-bits gehele getalwaarde.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waar begonnen moet worden met het nemen van bytes voor conversie |

### Retourwaarde

Ongetekende 64-bits gehele getalwaarde die voortkomt uit de conversie

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)