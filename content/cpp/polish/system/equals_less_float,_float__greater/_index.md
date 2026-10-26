---
title: Equals< float, float >()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Specjalizacja dla wartości zmiennoprzecinkowych o pojedynczej precyzji. Chociaż dwa NaN typu zmiennoprzecinkowego są zdefiniowane w IEC 60559:1989 jako zawsze nierówne, kontrakt dla System.Object.Equals wymaga, aby nadpisania spełniały wymagania operatora równoważności. Dlatego System.Double.Equals i System.Single.Equals zwracają True przy porównywaniu dwóch NaN, podczas gdy operator równości zwraca False w takim przypadku, zgodnie ze standardem."
type: docs
weight: 2705
url: /pl/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) funkcja

Specjalizacja dla wartości zmiennoprzecinkowych o pojedynczej precyzji. Chociaż dwa NaN typu zmiennoprzecinkowego są zdefiniowane w IEC 60559:1989 jako zawsze nierówne, kontrakt dla [System.Object.Equals](../object/equals/) wymaga, aby nadpisania spełniały wymagania operatora równoważności. Dlatego System.Double.Equals i System.Single.Equals zwracają True przy porównywaniu dwóch NaN, podczas gdy operator równości zwraca False w takim przypadku, zgodnie ze standardem.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| a | const **float**\& | Pierwszy porównywany |
| b | const **float**\& | Drugi porównywany |

### Wartość zwracana

True jeśli obie wartości są NaN lub są równe, w przeciwnym razie - false

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)