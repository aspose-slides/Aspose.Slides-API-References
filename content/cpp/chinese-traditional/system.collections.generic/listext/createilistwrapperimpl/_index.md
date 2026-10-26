---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides for C++ API 參考
description: IListWrapper 參考型別的實作輔助程式。
type: docs
weight: 14
url: /zh-hant/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() 方法


[IListWrapper](../../../system.collections/ilistwrapper/) 參考型別的實作輔助程式。

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() 方法


[IListWrapper](../../../system.collections/ilistwrapper/) 值型別的實作輔助程式。

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() 方法


[IListWrapper](../../../system.collections/ilistwrapper/) 其他型別的實作輔助程式。

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IList](../../../system.collections/ilist/)
* 類別 [ListExt](../)
* 結構 [IsSmartPtr](../../../system/issmartptr/)
* 結構 [IsBoxable](../../../system/isboxable/)
* 命名空間 [System::Collections::Generic](../../)
* 函式庫 [Aspose.Slides](../../../)