---
title: Compare()
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare deux valeurs.
type: docs
weight: 2692
url: /fr/system/compare/
---
## System::Compare(const TA\&, const TB\&) fonction

Compare deux valeurs.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### Valeur de retour

- 1 si **a** est inférieur à **b** ; 0 si les valeurs sont égales ; 1 si **a** est supérieur à **b**

## System::Compare(const TA\&, const TB\&) fonction

Compare deux valeurs à virgule flottante.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TA | The type of the first comparand |
| TB | The type of the second comparand |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const TA\& | The first comparand |
| b | const TB\& | The second comparand |

### Valeur de retour

- 1 si **a** est inférieur à **b** ; 0 si les valeurs sont égales ; 1 si **a** est supérieur à **b**

## Voir aussi

* Namespace [System](../)
* Library [Aspose.Slides](../../)