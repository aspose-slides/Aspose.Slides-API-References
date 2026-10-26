---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides für C++ API-Referenz
description: IListWrapper Implementierungshilfe für Referenztypen.
type: docs
weight: 14
url: /de/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() Methode

[IListWrapper](../../../system.collections/ilistwrapper/) Implementierungshilfe für Referenztypen.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() Methode

[IListWrapper](../../../system.collections/ilistwrapper/) Implementierungshilfe für Werttypen.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() Methode

[IListWrapper](../../../system.collections/ilistwrapper/) Implementierungshilfe für andere Typen.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)