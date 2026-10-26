---
title: get_PathTypes()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu.
type: docs
weight: 27
url: /pl/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() metoda


Zwraca tablicę wartości bajtowych określających typ każdego punktu w ścieżce elementu.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## Uwagi


**0** Wskazuje, że punkt jest początkiem figury.

**1** Wskazuje, że punkt jest jednym z dwóch końcowych punktów linii.

**3** Wskazuje, że punkt jest końcowym lub punktem kontrolnym krzywej Béziera trzeciego stopnia.

**7** Maskuje wszystkie bity oprócz trzech najmniej znaczących bitów, które określają typ punktu.

**16** Określa, że odpowiadający segment jest przerywany.

**32** Określa, że punkt jest znacznikiem.

**128** Określa, że punkt jest ostatnim punktem w zamkniętej podścieżce (figurze).

**129** Wskazuje na punkt danych, który jest jednocześnie końcowym punktem segmentu linii oraz ostatnim punktem zamkniętej podścieżki.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ShapeElement](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)