---
title: operator()()
second_title: Aspose.Slides pour C++ API Référence
description: Compare les types de pointeurs implémentant l'interface IComparable.
type: docs
weight: 1
url: /fr/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const méthode


Compare les types de pointeurs implémentant l’interface [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valeur LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valeur RHS. |

### Valeur de retour

Vrai si **a** est considéré comme inférieur à **b**, faux sinon.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const méthode


Compare les types de pointeurs ne mettant pas en œuvre l’interface [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Q | Type à comparer. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valeur LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valeur RHS. |

### Valeur de retour

Vrai si **a** est considéré comme inférieur à **b**, faux sinon.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Espace de noms [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)