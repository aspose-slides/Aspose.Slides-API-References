---
title: operator()()
second_title: Aspose.Slides for C++ API 參考手冊
description: 比較實作 IComparable 介面的指標型別。
type: docs
weight: 1
url: /zh-hant/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const 方法

比較實作 [IComparable](../../../system/icomparable/) 介面的指標型別。

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Q | 要比較的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 左值。 |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 右值。 |

### 傳回值

如果 **a** 被視為小於 **b**，則回傳 True，否則回傳 false。

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const 方法

比較未實作 [IComparable](../../../system/icomparable/) 介面的指標型別。

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| Q | 要比較的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 左值。 |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | 右值。 |

### 傳回值

如果 **a** 被視為小於 **b**，則回傳 True，否則回傳 false。

## 另請參閱

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IComparable](../../../system/icomparable/)
* 結構 [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* 結構 [ComparerType< SharedPtr< T > >](../)
* 命名空間 [System::Collections::Generic::Details](../../)
* 函式庫 [Aspose.Slides](../../../)