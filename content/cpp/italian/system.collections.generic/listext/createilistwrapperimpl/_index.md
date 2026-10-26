---
title: CreateIListWrapperImpl()
second_title: Riferimento API di Aspose.Slides per C++
description: Assistente di implementazione IListWrapper per i tipi di riferimento.
type: docs
weight: 14
url: /it/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() metodo

[IListWrapper](../../../system.collections/ilistwrapper/) assistente di implementazione per i tipi di riferimento.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metodo

[IListWrapper](../../../system.collections/ilistwrapper/) assistente di implementazione per i tipi di valore.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metodo

[IListWrapper](../../../system.collections/ilistwrapper/) assistente di implementazione per altri tipi.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IList](../../../system.collections/ilist/)
* Classe [ListExt](../)
* Struttura [IsSmartPtr](../../../system/issmartptr/)
* Struttura [IsBoxable](../../../system/isboxable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)