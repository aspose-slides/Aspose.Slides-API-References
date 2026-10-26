---
title: ComparerType
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare les éléments en utilisant la sémantique 'less'.
type: docs
weight: 144
url: /fr/system.collections.generic.details/comparertype/
---
## ComparerType struct

Compare les éléments en utilisant la sémantique 'less'.

```cpp
template<typename T>class ComparerType
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type des éléments comparés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compare les types de valeur implémentant l'interface [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compare les types de valeur primitifs et les objets n'implémentant pas l'interface [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Compare les types à virgule flottante. |

## Voir aussi

* Espace de noms [System::Collections::Generic::Details](../)
* Bibliothèque [Aspose.Slides](../../)