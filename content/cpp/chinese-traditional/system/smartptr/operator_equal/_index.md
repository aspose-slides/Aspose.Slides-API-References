---
title: operator=()
second_title: Aspose.Slides for C++ API 參考
description: 移動賦值 SmartPtr 物件。x 變得不可使用。
type: docs
weight: 27
url: /zh-hant/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_\&&) 方法

移動賦值 [SmartPtr](../) 物件。x 變得不可使用。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 指向移動賦值的指標。 |

### 傳回值

此物件的參考。

## SmartPtr::operator=(const SmartPtr_\&) 方法

複製賦值 [SmartPtr](../) 物件。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | 指向複製賦值的指標。 |

### 傳回值

此物件的參考。

## SmartPtr::operator=(const SmartPtr\<Q\>\&) 方法

複製賦值 [SmartPtr](../) 物件。執行必要的型別轉換。

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| Q | x 所指向的物件類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | 指向複製賦值的指標。 |

### 傳回值

此物件的參考。

## SmartPtr::operator=(Pointee_ *) 方法

將原始指標指派給 [SmartPtr](../) 物件。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | 要指派的指標值。 |

### 傳回值

此物件的參考。

## SmartPtr::operator=(std::nullptr_t) 方法

將指標值設定為 nullptr。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### 傳回值

此物件的參考。

## 另請參閱

* 型別別名 [SmartPtr_](../smartptr_/)
* 型別別名 [Pointee_](../pointee_/)
* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)