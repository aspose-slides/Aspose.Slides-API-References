---
title: UnknownToObject()
second_title: Aspose.Slides for C++ API 参考
description: 将未知类型转换为 Object，处理智能指针类型和值类型两种情况。
type: docs
weight: 118
url: /zh/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) 方法

将未知类型转换为[Object](../../object/)，同时处理智能指针类型和值类型的情况。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要转换为[Object](../../object/)的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T | 要转换的[Object](../../object/)。 |

### 返回值

智能指针[Object](../../object/)，可以是已转换的指针或装箱的值。

## ObjectExt::UnknownToObject(const T&) 方法

将未知类型转换为[Object](../../object/)，同时处理智能指针类型和值类型的情况。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要转换为[Object](../../object/)的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 要转换的[Object](../../object/)。 |

### 返回值

智能指针[Object](../../object/)，可以是已转换的指针或装箱的值。

## 另请参阅

* 类 [SmartPtr](../../smartptr/)
* 类 [Object](../../object/)
* 类 [ObjectExt](../)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)