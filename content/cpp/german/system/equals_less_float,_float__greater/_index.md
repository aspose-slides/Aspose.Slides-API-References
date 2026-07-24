---
title: Equals< float, float >()
second_title: Aspose.Slides für C++ API-Referenz
description: "Spezialisierung für Gleitkommawerte mit einfacher Genauigkeit. Obwohl zwei Gleitkomma-NaNs gemäß IEC 60559:1989 immer als ungleich verglichen werden, verlangt der Vertrag für System.Object.Equals, dass Überschreibungen die Anforderungen an einen Äquivalenzoperator erfüllen. Daher geben System.Double.Equals und System.Single.Equals True zurück, wenn zwei NaNs verglichen werden, während der Gleichheitsoperator in diesem Fall False zurückgibt, wie vom Standard gefordert."
type: docs
weight: 2705
url: /de/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) Funktion


Spezialisierung für Gleitkommawerte mit einfacher Genauigkeit. Obwohl zwei Gleitkomma-NaNs laut IEC 60559:1989 immer als ungleich verglichen werden, verlangt der Vertrag für [System.Object.Equals](../object/equals/), dass Überschreibungen die Anforderungen an einen Äquivalenzoperator erfüllen. Deshalb geben System.Double.Equals und System.Single.Equals True zurück, wenn zwei NaNs verglichen werden, während der Gleichheitsoperator in diesem Fall False zurückgibt, wie vom Standard gefordert.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a | const **float**\& | Der erste Operand |
| b | const **float**\& | Der zweite Operand |

### Rückgabewert

True, wenn beide Werte NaN sind oder gleich sind, andernfalls - false

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)