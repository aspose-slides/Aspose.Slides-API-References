---
title: AreFPNaN()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Szczegóły przestrzeni nazw
type: docs
weight: 1
url: /pl/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) funkcja

przestrzeń nazw [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Pierwszy typ zmiennoprzecinkowy. |
| T2 | Drugi typ zmiennoprzecinkowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs | T1 | Pierwsza wartość zmiennoprzecinkowa. |
| rhs | T2 | Druga wartość zmiennoprzecinkowa. |

### Wartość zwracana

True jeśli zarówno **lhs**, jak i **rhs** są wartościami zmiennoprzecinkowymi, false w przeciwnym razie.

## Uwagi

Sprawdza, czy dwie wartości zmiennoprzecinkowe są oboma NaN. Obsługuje sytuację, gdy obsługiwany jest nie-sygnalizujący NaN. 

## System::TestPredicates::AreFPNaN(T1, T2) funkcja

Sprawdza, czy dwie wartości zmiennoprzecinkowe są oboma NaN. Obsługuje sytuację, gdy nie-sygnalizujący NaN nie jest obsługiwany.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| T1 | Pierwszy typ zmiennoprzecinkowy. |
| T2 | Drugi typ zmiennoprzecinkowy. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| lhs | T1 | Pierwsza wartość zmiennoprzecinkowa. |
| rhs | T2 | Druga wartość zmiennoprzecinkowa. |

### Wartość zwracana

Zawsze zwraca false, ponieważ wartość NaN nie jest obsługiwana.

## Zobacz także

* Przestrzeń nazw [System::TestPredicates](../)
* Biblioteka [Aspose.Slides](../../)