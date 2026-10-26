---
title: Ref()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy referencję do obiektu DynamicWeakPtr. Używany przez translator przy przekazywaniu argumentów funkcji przez referencję.
type: docs
weight: 2458
url: /pl/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) funkcja

Tworzy referencję do obiektu [DynamicWeakPtr](../dynamicweakptr/). Używany przez translator przy przekazywaniu argumentów funkcji przez referencję.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ wskazywanego obiektu. |
| trunkMode | Tryb samego inteligentnego wskaźnika. |
| weakLeafs | Indeksy argumentów szablonu, dla których należy wywołać metodę SetTemplateWeakPtr. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Inteligentny wskaźnik, do którego ma zostać utworzona referencja. |

### Wartość zwracana

Referencja do inteligentnego wskaźnika.

## System::Ref(T\&) funkcja

Funkcja pomocnicza służąca do uzyskiwania referencji do obiektów. Używana, aby zapewnić, że [System::DynamicWeakPtr](../dynamicweakptr/) aktualizuje odwołany obiekt po przypisaniach.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T | Typ, do którego ma zostać utworzona referencja. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| value | T\& | Wartość, do której ma zostać utworzona referencja. |

### Wartość zwracana

Referencja do wartości przekazanej do tej funkcji.

## Zobacz także

* Klasa [DynamicWeakPtr](../dynamicweakptr/)
* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)