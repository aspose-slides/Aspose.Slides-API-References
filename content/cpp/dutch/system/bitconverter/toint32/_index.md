---
title: ToInt32()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert vier bytes van de opgegeven array, beginnend bij de opgegeven index, naar een 32-bit geheel getalwaarde.
type: docs
weight: 66
url: /nl/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) methode


Converteert vier bytes van de opgegeven array, beginnend bij de opgegeven index, naar een 32-bits geheel getalwaarde.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop moet beginnen met het nemen van bytes voor conversie |

### Retourwaarde

32-bits geheel getalwaarde die voortkomt uit de conversie

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) methode


Converteert vier bytes van de opgegeven array, beginnend bij de opgegeven index, naar een 32-bits geheel getalwaarde.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop moet beginnen met het nemen van bytes voor conversie |

### Retourwaarde

32-bits geheel getalwaarde die voortkomt uit de conversie

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)