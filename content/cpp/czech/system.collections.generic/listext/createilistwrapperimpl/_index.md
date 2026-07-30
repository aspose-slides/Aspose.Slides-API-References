---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides pro C++ – reference API
description: Implementační pomocník IListWrapper pro referenční typy.
type: docs
weight: 14
url: /cs/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() metoda

[IListWrapper](../../../system.collections/ilistwrapper/) implementační pomocník pro referenční typy.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metoda

[IListWrapper](../../../system.collections/ilistwrapper/) implementační pomocník pro hodnotové typy.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metoda

[IListWrapper](../../../system.collections/ilistwrapper/) implementační pomocník pro ostatní typy.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IList](../../../system.collections/ilist/)
* Třída [ListExt](../)
* Struktura [IsSmartPtr](../../../system/issmartptr/)
* Struktura [IsBoxable](../../../system/isboxable/)
* Jmenný prostor [System::Collections::Generic](../../)
* Knihovna [Aspose.Slides](../../../)