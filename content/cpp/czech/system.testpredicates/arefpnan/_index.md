---
title: AreFPNaN()
second_title: Aspose.Slides pro C++ referenci API
description: Podrobnosti jmenného prostoru
type: docs
weight: 1
url: /cs/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) funkce

namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Návratová hodnota

True, pokud jsou **lhs** i **rhs** hodnoty s plovoucí desetinnou čárkou, false jinak.

## Poznámky

Kontroluje, že dvě hodnoty s plovoucí desetinnou čárkou jsou obě NaN. Ošetřuje situaci, kdy je podporována nesignální NaN. 

## System::TestPredicates::AreFPNaN(T1, T2) funkce

Kontroluje, že dvě hodnoty s plovoucí desetinnou čárkou jsou obě NaN. Ošetřuje situaci, kdy není podporována nesignální NaN.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Návratová hodnota

Vždy vrací false, protože hodnota NaN není podporována.

## Viz také

* Jmenný prostor [System::TestPredicates](../)
* Knihovna [Aspose.Slides](../../)