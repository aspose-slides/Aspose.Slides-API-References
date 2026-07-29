---
title: AreFPNaN()
second_title: Aspose.Slides för C++ API-referens
description: namespace Detaljer
type: docs
weight: 1
url: /sv/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) funktion


namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Returvärde

Sant om både **lhs** och **rhs** är flyttal, falskt annars.
## Anmärkningar


Kontrollerar att två flyttal är båda NaN. Hanterar situation när icke-signalerande NaN stöds. 
## System::TestPredicates::AreFPNaN(T1, T2) funktion


Kontrollerar att två flyttal är båda NaN. Hanterar situation när icke-signalerande NaN inte stöds.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Returvärde

Returnerar alltid falskt eftersom NaN-värdet inte stöds.

## Se även

* Namnrymd [System::TestPredicates](../)
* Bibliotek [Aspose.Slides](../../)