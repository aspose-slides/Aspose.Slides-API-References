---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides برای مرجع API C++
description: کمک‌کننده پیاده‌سازی IListWrapper برای انواع مرجع.
type: docs
weight: 14
url: /fa/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() متد

[IListWrapper](../../../system.collections/ilistwrapper/) کمک‌کننده پیاده‌سازی برای انواع مرجع.

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() متد

[IListWrapper](../../../system.collections/ilistwrapper/) کمک‌کننده پیاده‌سازی برای انواع مقدار.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() متد

[IListWrapper](../../../system.collections/ilistwrapper/) کمک‌کننده پیاده‌سازی برای سایر انواع.

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## مراجع

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IList](../../../system.collections/ilist/)
* کلاس [ListExt](../)
* ساختار [IsSmartPtr](../../../system/issmartptr/)
* ساختار [IsBoxable](../../../system/isboxable/)
* فضای‌نام [System::Collections::Generic](../../)
* کتابخانه [Aspose.Slides](../../../)