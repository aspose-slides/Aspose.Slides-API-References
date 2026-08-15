---
title: operator=()
second_title: Aspose.Slides for C++ API 參考
description: 移動指派智慧指標。
type: docs
weight: 27
url: /zh-hant/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) 方法

移動指派智慧指標。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 來源的移動指派指標。 |

### 返回值

自身參照。

## DynamicWeakPtr::operator=(const SmartPtr_&) 方法

複製指派智慧指標。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | 來源的複製指派指標。 |

### 返回值

自身參照。

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) 方法

複製指派智慧指標。

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Q | 來源指向類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 來源的複製指派指標。 |

### 返回值

自身參照。

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) 方法

指派智慧指標。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | 指標值。 |

### 返回值

自身參照。

## DynamicWeakPtr::operator=(std::nullptr_t) 方法

將智慧指標設為 null。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### 返回值

自身參照。

## 另請參閱

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* 類別 [DynamicWeakPtr](../)
* 類別 [SmartPtr](../../smartptr/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)