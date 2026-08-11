---
title: CreateIListWrapperImpl()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: مساعد تنفيذ IListWrapper للأنواع المرجعية.
type: docs
weight: 14
url: /ar/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() طريقة


[IListWrapper](../../../system.collections/ilistwrapper/) مساعد التنفيذ للأنواع المرجعية.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() طريقة


[IListWrapper](../../../system.collections/ilistwrapper/) مساعد التنفيذ للأنواع القيمية.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() طريقة


[IListWrapper](../../../system.collections/ilistwrapper/) مساعد التنفيذ للأنواع الأخرى.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IList](../../../system.collections/ilist/)
* فئة [ListExt](../)
* بنية [IsSmartPtr](../../../system/issmartptr/)
* بنية [IsBoxable](../../../system/isboxable/)
* مساحة اسم [System::Collections::Generic](../../)
* مكتبة [Aspose.Slides](../../../)