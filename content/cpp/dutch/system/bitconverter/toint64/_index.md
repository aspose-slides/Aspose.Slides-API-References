---
title: ToInt64()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert acht bytes van de opgegeven array beginnend bij de opgegeven index naar een 64-bits geheel getalwaarde.
type: docs
weight: 79
url: /nl/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) methode


Converteert acht bytes van de opgegeven array beginnend bij de opgegeven index naar een 64-bits geheel getalwaarde.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop bytes voor conversie moeten worden genomen |

### Retourwaarde

64-bits geheel getalwaarde die het resultaat is van de conversie

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) methode


Converteert acht bytes van de opgegeven array beginnend bij de opgegeven index naar een 64-bits geheel getalwaarde.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView die bytes bevat om te converteren |
| startIndex | int | [Index](../../index/) in de array waarop bytes voor conversie moeten worden genomen |

### Retourwaarde

64-bits geheel getalwaarde die het resultaat is van de conversie

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)