---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: ตัวช่วยการทำงานของ IListWrapper สำหรับประเภทอ้างอิง.
type: docs
weight: 14
url: /th/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() เมธอด

[IListWrapper](../../../system.collections/ilistwrapper/) ตัวช่วยการทำงานสำหรับประเภทอ้างอิง.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() เมธอด

[IListWrapper](../../../system.collections/ilistwrapper/) ตัวช่วยการทำงานสำหรับประเภทค่า.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() เมธอด

[IListWrapper](../../../system.collections/ilistwrapper/) ตัวช่วยการทำงานสำหรับประเภทอื่น.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IList](../../../system.collections/ilist/)
* คลาส [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* เนมสเปซ [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)