---
title: ObjectToUnknown()
second_title: Aspose.Slides for C++ API 参考
description: 将 Object 转换为未知类型，处理智能指针类型和装箱值情况。
type: docs
weight: 131
url: /zh/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) 方法


将 [Object](../../object/) 转换为未知类型，处理智能指针类型和装箱值情况。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要转换 [Object](../../object/) 为的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | 要转换的 [Object](../../object/)。 |

### 返回值

可以是未装箱的值或已转换的指针。

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) 方法


将 [Object](../../object/) 转换为未知类型，处理智能指针类型和装箱值情况。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要转换 [Object](../../object/) 为的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | 要转换的 [Object](../../object/)。 |

### 返回值

可以是未装箱的值或已转换的指针。

## 另请参见

* 类 [SmartPtr](../../smartptr/)
* 类 [Object](../../object/)
* 类 [ObjectExt](../)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)