---
title: ToSingle()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert vier bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een drijvende-kommagetalwaarde met enkelvoudige precisie.
type: docs
weight: 131
url: /nl/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) methode

Converteert vier bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een drijvende-kommagetalwaarde met enkelvoudige precisie.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop moet worden begonnen met het nemen van bytes voor conversie |

### Retourwaarde

Drijvende-kommagetalwaarde met enkelvoudige precisie die voortkomt uit de conversie

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) methode

Converteert vier bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een drijvende-kommagetalwaarde met enkelvoudige precisie.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop moet worden begonnen met het nemen van bytes voor conversie |

### Retourwaarde

Drijvende-kommagetalwaarde met enkelvoudige precisie die voortkomt uit de conversie

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)