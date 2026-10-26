---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: 参照型の IListWrapper 実装ヘルパー。
type: docs
weight: 14
url: /ja/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() メソッド


[IListWrapper](../../../system.collections/ilistwrapper/) 参照型の実装ヘルパー。

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() メソッド


[IListWrapper](../../../system.collections/ilistwrapper/) 値型の実装ヘルパー。

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() メソッド


[IListWrapper](../../../system.collections/ilistwrapper/) その他の型の実装ヘルパー。

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IList](../../../system.collections/ilist/)
* クラス [ListExt](../)
* Struct [IsSmartPtr](../../../system/issmartptr/)
* Struct [IsBoxable](../../../system/isboxable/)
* 名前空間 [System::Collections::Generic](../../)
* ライブラリ [Aspose.Slides](../../../)