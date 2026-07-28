---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides for C++ API referencia
description: IListWrapper implementációs segéd a referenciatípusokhoz.
type: docs
weight: 14
url: /hu/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() metódus

[IListWrapper](../../../system.collections/ilistwrapper/) implementációs segéd a referenciatípusokhoz.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metódus

[IListWrapper](../../../system.collections/ilistwrapper/) implementációs segéd az értéktípusokhoz.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() metódus

[IListWrapper](../../../system.collections/ilistwrapper/) implementációs segéd egyéb típusokhoz.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IList](../../../system.collections/ilist/)
* Osztály [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* Névtér [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)