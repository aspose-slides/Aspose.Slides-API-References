---
title: MakeYieldEnumerator()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen IEnumerator aus einer Yield-Funktion.
type: docs
weight: 2432
url: /de/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) Funktion

Erstellt einen IEnumerator aus einer Yield-Funktion.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Der Typ der Elemente in der Sequenz |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Die auszuführende Yield-Funktion |

### Rückgabewert

Gemeinsamer Zeiger auf den IEnumerator

## Siehe auch

* Typedef [SharedPtr](../sharedptr/)
* Klasse [IEnumerator](../../system.collections.generic/ienumerator/)
* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)