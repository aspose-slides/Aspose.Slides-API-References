---
title: DynamicCastArray()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Wykonuje rzutowanie elementów określonej tablicy na inny typ.
type: docs
weight: 2991
url: /pl/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) function

Wykonuje rzutowanie elementów określonej tablicy na inny typ.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| To | Typ **To**, do którego należy przekonwertować elementy określonej tablicy |
| From | Typ elementów **From**, które mają zostać przekonwertowane |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Wskaźnik współdzielony do tablicy zawierającej elementy do rzutowania |

### Wartość zwracana

Wskaźnik do nowej tablicy zawierającej elementy typu **To**, równoważne elementom **from**

Przestarzałe
:   Dodano dla zachowania kompatybilności wstecznej. Użyj ExplicitCast zamiast tego.

## Zobacz także

* Definicja typu [SharedPtr](../sharedptr/)
* Klasa [Array](../array/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)