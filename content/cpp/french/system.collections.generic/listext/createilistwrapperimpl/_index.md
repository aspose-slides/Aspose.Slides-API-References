---
title: CreateIListWrapperImpl()
second_title: Référence API Aspose.Slides pour C++
description: IListWrapper assistant d'implémentation pour les types de référence.
type: docs
weight: 14
url: /fr/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() méthode

[IListWrapper](../../../system.collections/ilistwrapper/) assistant d'implémentation pour les types de référence.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() méthode

[IListWrapper](../../../system.collections/ilistwrapper/) assistant d'implémentation pour les types de valeur.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() méthode

[IListWrapper](../../../system.collections/ilistwrapper/) assistant d'implémentation pour les autres types.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IList](../../../system.collections/ilist/)
* classe [ListExt](../)
* structure [IsSmartPtr](../../../system/issmartptr/)
* structure [IsBoxable](../../../system/isboxable/)
* espace de noms [System::Collections::Generic](../../)
* bibliothèque [Aspose.Slides](../../../)