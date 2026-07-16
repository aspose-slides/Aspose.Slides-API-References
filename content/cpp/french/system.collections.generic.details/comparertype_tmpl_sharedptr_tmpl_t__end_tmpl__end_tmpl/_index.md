---
title: ComparerType< SharedPtr< T > >
second_title: Référence de l'API Aspose.Slides pour C++
description: Compare les éléments en utilisant la sémantique 'less'.
type: docs
weight: 157
url: /fr/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct


Compare les éléments en utilisant la sémantique 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type des éléments comparés. |
## Méthodes

| Méthode | Description |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compare les types de pointeur implémentant l'interface [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Compare les types de pointeur n'implémentant pas l'interface [IComparable](../../system/icomparable/). |

## Voir aussi

* Espace de noms [System::Collections::Generic::Details](../)
* Bibliothèque [Aspose.Slides](../../)