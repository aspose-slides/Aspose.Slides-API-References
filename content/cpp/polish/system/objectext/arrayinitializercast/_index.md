---
title: ArrayInitializerCast()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Konwertuje fundamentalne wartości tablicy (co C# robi domyślnie, ale C++ najwyraźniej nie).
type: docs
weight: 209
url: /pl/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) metoda

Konwertuje fundamentalne wartości tablicy (co C# robi domyślnie, ale C++ najwyraźniej nie).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| To | Typ docelowy. |
| From | Typy źródłowe. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| args | From ... | Wartości do konwersji i wstawienia do docelowej tablicy. |

### Wartość zwracana

[Array](../../array/) zawierający przekonwertowane kopie wszystkich argumentów w tej samej kolejności.

## Zobacz także

* Klasa [ObjectExt](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)