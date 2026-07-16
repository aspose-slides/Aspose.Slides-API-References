---
title: AreFPNaN()
second_title: Aspose.Slides pour C++ Référence API
description: espace de noms Details
type: docs
weight: 1
url: /fr/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) fonction


namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Valeur de retour

Vrai si **lhs** et **rhs** sont tous deux des valeurs en virgule flottante, false sinon.
## Remarques


Vérifie que deux valeurs en virgule flottante sont toutes deux NaN. Gère la situation lorsque le NaN non signalant est pris en charge. 
## System::TestPredicates::AreFPNaN(T1, T2) fonction


Vérifie que deux valeurs en virgule flottante sont toutes deux NaN. Gère la situation lorsque le NaN non signalant n'est pas pris en charge.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | First floating point type. |
| T2 | Second floating point type. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhs | T1 | First floating point value. |
| rhs | T2 | Second floating point value. |

### Valeur de retour

Retourne toujours false car la valeur NaN n'est pas prise en charge.

## Voir aussi

* Espace de noms [System::TestPredicates](../)
* Bibliothèque [Aspose.Slides](../../)