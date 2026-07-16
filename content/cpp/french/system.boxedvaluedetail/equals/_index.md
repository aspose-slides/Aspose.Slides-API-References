---
title: Equals()
second_title: Référence API Aspose.Slides pour C++
description: Détermine l'égalité de la valeur spécifiée en utilisant l'opérateur ==().
type: docs
weight: 66
url: /fr/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) fonction

Détermine l'égalité de la valeur spécifiée en utilisant [operator==()](../../system/operator_equal_equal/).

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| The | type des valeurs comparées |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value1 | T | Le premier comparand |
| value2 | T | Le second comparand |

### Valeur de retour

True si les valeurs spécifiées sont égales selon [operator==()](../../system/operator_equal_equal/), sinon - false

## System::BoxedValueDetail::Equals(T, T) fonction

Détermine l'égalité de la valeur spécifiée en utilisant la méthode [System::Object::Equals()](../../system/object/equals/).

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| The | type des valeurs comparées |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value1 | T | Le premier comparand |
| value2 | T | Le second comparand |

### Valeur de retour

True si les valeurs spécifiées sont égales selon la méthode [Equals()](./), sinon - false

## Voir aussi

* Espace de noms [System::BoxedValueDetail](../)
* Bibliothèque [Aspose.Slides](../../)