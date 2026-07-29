---
title: TryGetFirst()
second_title: Aspose.Slides för C++ API-referens
description: Försöker hämta det första elementet i samlingen.
type: docs
weight: 248
url: /sv/system.collections.generic.details/trygetfirst/
---
## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, bool\&) funktion


Försöker hämta det första elementet i samlingen.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, bool &found)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av samlingens element. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Den samling från vilken ett element ska hämtas. |
| found | **bool**\& | Utdataparameter. Returnerar true när samlingen innehåller något element. Annars returneras false. |

### Returvärde

Returnerar det första elementet i samlingen. Standardvärdet för typen returneras när samlingen är tom.

## System::Collections::Generic::Details::TryGetFirst(IEnumerable\<T\>\&, const Func\<T, bool\>\&, bool\&) funktion


Försöker hämta det första elementet i samlingen som uppfyller predikatfunktionen.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetFirst(IEnumerable<T> &enumerable, const Func<T, bool> &predicate, bool &found)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen av samlingens element. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Den samling från vilken ett element ska hämtas. |
| predicate | const [Func](../../system/func/)\<T, **bool**\>\& | Predikatfunktionen. |
| found | **bool**\& | Utdataparameter. Returnerar true när samlingen innehåller något element. Annars returneras false. |

### Returvärde

Returnerar det första elementet i samlingen. Standardvärdet för typen returneras när inget element som uppfyller den angivna predikatfunktionen hittas.

## Se även

* Klass [IEnumerable](../../system.collections.generic/ienumerable/)
* Klass [Func](../../system/func/)
* Namnrymd [System::Collections::Generic::Details](../)
* Bibliotek [Aspose.Slides](../../)