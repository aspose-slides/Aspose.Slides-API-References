---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides voor C++ API-referentie
description: IListWrapper implementatiehulp voor referentietypen.
type: docs
weight: 14
url: /nl/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() methode


[IListWrapper](../../../system.collections/ilistwrapper/) implementatiehulp voor referentietypen.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() methode


[IListWrapper](../../../system.collections/ilistwrapper/) implementatiehulp voor waardetypen.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() methode


[IListWrapper](../../../system.collections/ilistwrapper/) implementatiehulp voor andere typen.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)