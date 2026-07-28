---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides dla dokumentacji API C++
description: Pomocnik implementacji IListWrapper dla typów referencyjnych.
type: docs
weight: 14
url: /pl/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() metoda


[IListWrapper](../../../system.collections/ilistwrapper/) pomocnik implementacji dla typów referencyjnych.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metoda


[IListWrapper](../../../system.collections/ilistwrapper/) pomocnik implementacji dla typów wartościowych.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metoda


[IListWrapper](../../../system.collections/ilistwrapper/) pomocnik implementacji dla innych typów.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IList](../../../system.collections/ilist/)
* Klasa [ListExt](../)
* Struktura [IsSmartPtr](../../../system/issmartptr/)
* Struktura [IsBoxable](../../../system/isboxable/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)