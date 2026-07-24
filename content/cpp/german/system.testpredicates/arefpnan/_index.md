---
title: AreFPNaN()
second_title: Aspose.Slides für C++ API-Referenz
description: Namespace-Details
type: docs
weight: 1
url: /de/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) Funktion


namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Rückgabewert

Wahr, wenn sowohl **lhs** als auch **rhs** Gleitkommawerte sind, sonst falsch.
## Bemerkungen


Überprüft, dass zwei Gleitkommawerte beide NaN sind. Behandelt die Situation, wenn nichtsignalisierendes NaN unterstützt wird.
## System::TestPredicates::AreFPNaN(T1, T2) Funktion


Überprüft, dass zwei Gleitkommawerte beide NaN sind. Behandelt die Situation, wenn nichtsignalisierendes NaN nicht unterstützt wird.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Rückgabewert

Gibt immer false zurück, da NaN-Wert nicht unterstützt wird.

## Siehe auch

* Namensraum [System::TestPredicates](../)
* Library [Aspose.Slides](../../)