---
title: AreFPNaN()
second_title: Aspose.Slides voor C++ API-referentie
description: naamruimte Details
type: docs
weight: 1
url: /nl/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) functie

naamruimte [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Eerste floating point type. |
| T2 | Tweede floating point type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | T1 | Eerste floating point waarde. |
| rhs | T2 | Tweede floating point waarde. |

### Retourwaarde

Waar als zowel **lhs** als **rhs** floating point waarden zijn, anders onwaar.

## Opmerkingen

Controleert of twee floating point waarden beide NaN's zijn. Behandelt de situatie wanneer een non-signalling NaN wordt ondersteund. 

## System::TestPredicates::AreFPNaN(T1, T2) functie

Controleert of twee floating point waarden beide NaN's zijn. Behandelt de situatie wanneer een non-signalling NaN niet wordt ondersteund.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Eerste floating point type. |
| T2 | Tweede floating point type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lhs | T1 | Eerste floating point waarde. |
| rhs | T2 | Tweede floating point waarde. |

### Retourwaarde

Geeft altijd onwaar terug omdat de NaN-waarde niet wordt ondersteund.

## Zie ook

* Naamruimte [System::TestPredicates](../)
* Bibliotheek [Aspose.Slides](../../)