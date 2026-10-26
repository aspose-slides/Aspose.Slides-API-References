---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides για C++ Αναφορά API
description: βοηθός υλοποίησης IListWrapper για τύπους αναφοράς.
type: docs
weight: 14
url: /el/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() μέθοδος

[IListWrapper](../../../system.collections/ilistwrapper/) βοηθός υλοποίησης για τύπους αναφοράς.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() μέθοδος

[IListWrapper](../../../system.collections/ilistwrapper/) βοηθός υλοποίησης για τύπους τιμών.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() μέθοδος

[IListWrapper](../../../system.collections/ilistwrapper/) βοηθός υλοποίησης για άλλα τύπους.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections/ilist/)
* Class [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)