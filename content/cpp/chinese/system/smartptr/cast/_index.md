---
title: Cast()
second_title: Aspose.Slides 的 C++ API 参考
description: 将指针转换为其本身类型。
type: docs
weight: 287
url: /zh/system/smartptr/cast/
---
## SmartPtr::Cast() const 方法

将指针转换为其本身类型。

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Y | 指向对象的目标类型。 |
| Check | 如果没有可用的转换，则抛出异常的标志。 |

### 返回值

已更改类型的指针，始终为共享模式。

## SmartPtr::Cast() const 方法

使用 static_cast 将指针转换为基类类型。

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Y | 指向对象的目标类型。 |
| Check | 如果没有可用的转换，则抛出异常的标志。 |

### 返回值

已更改类型的指针，始终为共享模式。

## SmartPtr::Cast() const 方法

使用 dynamic_cast 将指针转换为派生类类型。

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Y | 指向对象的目标类型。 |
| Check | 如果没有可用的转换，则抛出异常的标志。 |

### 返回值

已更改类型的指针，始终为共享模式。如果没有可用的转换，则抛出 InvalidCastException。

## SmartPtr::Cast() const 方法

使用 dynamic_cast 将指针转换为派生类类型。

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Y | 指向对象的目标类型。 |
| Check | 如果没有可用的转换，则抛出异常的标志。 |

### 返回值

已更改类型的指针，始终为共享模式。如果没有可用的转换，则返回 nullptr。

## 另请参见

* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)