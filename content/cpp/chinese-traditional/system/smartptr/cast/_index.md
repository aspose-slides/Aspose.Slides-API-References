---
title: Cast()
second_title: Aspose.Slides for C++ API 參考
description: 將指標轉換為其自身的類型。
type: docs
weight: 287
url: /zh-hant/system/smartptr/cast/
---
## SmartPtr::Cast() const 方法

將指標轉換為其自身的類型。

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| Y | 目標指向物件的類型。 |
| Check | 若無法轉換則拋出例外的旗標。 |

### 返回值

返回已更改類型的指標，始終處於共享模式。

## SmartPtr::Cast() const 方法

使用 static_cast 將指標轉換為基礎類型。

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| Y | 目標指向物件的類型。 |
| Check | 若無法轉換則拋出例外的旗標。 |

### 返回值

返回已更改類型的指標，始終處於共享模式。

## SmartPtr::Cast() const 方法

使用 dynamic_cast 將指標轉換為衍生類型。

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| Y | 目標指向物件的類型。 |
| Check | 若無法轉換則拋出例外的旗標。 |

### 返回值

返回已更改類型的指標，始終處於共享模式。若無法轉換，拋出 InvalidCastException。

## SmartPtr::Cast() const 方法

使用 dynamic_cast 將指標轉換為衍生類型。

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| Y | 目標指向物件的類型。 |
| Check | 若無法轉換則拋出例外的旗標。 |

### 返回值

返回已更改類型的指標，始終處於共享模式。若無法轉換，返回 nullptr。

## 參見

* 類別 [SmartPtr](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)