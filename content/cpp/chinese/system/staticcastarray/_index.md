---
title: StaticCastArray()
second_title: Aspose.Slides C++ API 参考
description: 对指定数组的元素执行强制转换为不同类型的操作。针对 From 为 SmartPtr 对象的情况进行覆盖。
type: docs
weight: 2939
url: /zh/system/staticcastarray/
---
## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) 函数


执行将指定数组的元素强制转换为不同类型的操作。针对 From 为 [SmartPtr](../smartptr/) 对象的情况进行覆盖。

```cpp
template<typename To,typename From> std::enable_if_t<System::IsSmartPtr<From>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| To | 指定数组的元素要转换为的类型 |
| From | 要进行转换的数组元素的类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | 指向包含要转换元素的数组的共享指针 |

### 返回值

指向新数组的指针，该数组包含类型为 **To** 的元素，这些元素等价于 **from** 的元素

已弃用
:   为了向后兼容而添加。请改用 ExplicitCast。

## System::StaticCastArray(const System::SharedPtr\<System::Array\<From\>\>\&) 函数


执行将指定数组的元素强制转换为不同类型的操作。针对 From 为可装箱类型且 To 为 [Object](../object/)[] 的情况进行覆盖。

```cpp
template<typename To,typename From> std::enable_if_t<!System::IsSmartPtr<From>::value &&System::IsBoxable<From>::value &&std::is_same<To, System::SharedPtr<Object>>::value, System::SharedPtr<System::Array<To>>> System::StaticCastArray(const System::SharedPtr<System::Array<From>> &from)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| To | 指定数组的元素要转换为的类型 |
| From | 要进行转换的数组元素的类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [System::SharedPtr](../sharedptr/)\<[System::Array](../array/)\<From\>\>\& | 指向包含要转换元素的数组的共享指针 |

### 返回值

指向新数组的指针，该数组包含类型为 **To** 的元素，这些元素等价于 **from** 的元素

已弃用
:   为了向后兼容而添加。请改用 ExplicitCast。

## 另请参见

* 类型定义 [SharedPtr](../sharedptr/)
* 类 [Array](../array/)
* 类 [Object](../object/)
* 结构体 [IsSmartPtr](../issmartptr/)
* 结构体 [IsBoxable](../isboxable/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)