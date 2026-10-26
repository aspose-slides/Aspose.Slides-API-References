---
title: TryGetLast()
second_title: Aspose.Slides för C++ API-referens
description: Försöker hämta det sista elementet i samlingen.
type: docs
weight: 261
url: /sv/system.collections.generic.details/trygetlast/
---
## System::Collections::Generic::Details::TryGetLast(IEnumerable\<T\>\&, bool\&) funktion

Försöker hämta det sista elementet i samlingen.

```cpp
template<typename T> T System::Collections::Generic::Details::TryGetLast(IEnumerable<T> &enumerable, bool &found)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typen på samlingens element. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| enumerable | [IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\& | Samlingen från vilken ett element ska erhållas. |
| found | **bool**\& | Utdata-parametern. Returnerar true när samlingen innehåller något element. Annars returneras false. |

### Returvärde

Returnerar det sista elementet i samlingen. Standardvärdet för typen returneras när samlingen är tom.

## Se även

* Klass [IEnumerable](../../system.collections.generic/ienumerable/)
* Namnrymd [System::Collections::Generic::Details](../)
* Bibliotek [Aspose.Slides](../../)