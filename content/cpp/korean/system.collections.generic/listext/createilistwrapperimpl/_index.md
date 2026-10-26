---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides for C++ API 참조
description: 참조 형식에 대한 IListWrapper 구현 도우미.
type: docs
weight: 14
url: /ko/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) 참조 형식에 대한 구현 도우미.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) 값 형식에 대한 구현 도우미.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() method


[IListWrapper](../../../system.collections/ilistwrapper/) 기타 형식에 대한 구현 도우미.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IList](../../../system.collections/ilist/)
* 클래스 [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* 네임스페이스 [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)