---
title: ToUInt32()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert vier bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een ongetekende 32-bits geheel getalwaarde.
type: docs
weight: 105
url: /nl/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) methode


Converteert vier bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een ongetekend 32-bits geheel getal.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waar men moet beginnen met het nemen van bytes voor conversie |

### Retourwaarde

Ongetekende 32-bits geheel getal dat uit de conversie ontstaat

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) methode


Converteert vier bytes uit de opgegeven array, beginnend bij de opgegeven index, naar een ongetekend 32-bits geheel getal.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waar men moet beginnen met het nemen van bytes voor conversie |

### Retourwaarde

Ongetekende 32-bits geheel getal dat uit de conversie ontstaat

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)