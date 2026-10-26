---
title: MakeYieldEnumerable()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein IEnumerable aus einer Yield-Funktion.
type: docs
weight: 2419
url: /de/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) Funktion

Erstellt ein IEnumerable aus einer Yield-Funktion.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in der Sequenz |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Die Yield-Funktion, die ausgeführt werden soll |

### Rückgabewert

Gemeinsamer Zeiger auf das IEnumerable

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Klasse [IEnumerable](../../system.collections.generic/ienumerable/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)