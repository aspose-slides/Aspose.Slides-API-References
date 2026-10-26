---
title: CreateIListWrapperImpl()
second_title: Aspose.Slides for C++ API 参考
description: IListWrapper 实现帮助程序用于引用类型。
type: docs
weight: 14
url: /zh/system.collections.generic/listext/createilistwrapperimpl/
---
## ListExt::CreateIListWrapperImpl() 方法

[IListWrapper](../../../system.collections/ilistwrapper/) 实现帮助程序用于引用类型。

```cpp
template<typename T1> std::enable_if<System::IsSmartPtr<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() 方法

[IListWrapper](../../../system.collections/ilistwrapper/) 实现帮助程序用于值类型。

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&System::IsBoxable<T1>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## ListExt::CreateIListWrapperImpl() 方法

[IListWrapper](../../../system.collections/ilistwrapper/) 实现帮助程序用于其他类型。

```cpp
template<typename T1> std::enable_if<!System::IsSmartPtr<T1>::value &&!System::IsBoxable<T>::value, System::SharedPtr<System::Collections::IList>>::type System::Collections::Generic::ListExt<T>::CreateIListWrapperImpl()
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IList](../../../system.collections/ilist/)
* 类 [ListExt](../)
* 结构体 [IsSmartPtr](../../../system/issmartptr/)
* 结构体 [IsBoxable](../../../system/isboxable/)
* 命名空间 [System::Collections::Generic](../../)
* 库 [Aspose.Slides](../../../)