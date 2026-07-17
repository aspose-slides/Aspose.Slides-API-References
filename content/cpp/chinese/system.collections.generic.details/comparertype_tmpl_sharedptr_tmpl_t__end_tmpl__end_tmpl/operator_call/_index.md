---
title: operator()()
second_title: Aspose.Slides for C++ API 参考
description: 比较实现 IComparable 接口的指针类型。
type: docs
weight: 1
url: /zh/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const 方法

比较实现 [IComparable](../../../system/icomparable/) 接口的指针类型。

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 要比较的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 左侧值。 |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 右侧值。 |

### 返回值

如果 **a** 被视为小于 **b** 则返回 true，否则返回 false。

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const 方法

比较未实现 [IComparable](../../../system/icomparable/) 接口的指针类型。

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 要比较的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 左侧值。 |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 右侧值。 |

### 返回值

如果 **a** 被视为小于 **b** 则返回 true，否则返回 false。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IComparable](../../../system/icomparable/)
* 结构体 [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* 结构体 [ComparerType< SharedPtr< T > >](../)
* 命名空间 [System::Collections::Generic::Details](../../)
* 库 [Aspose.Slides](../../../)