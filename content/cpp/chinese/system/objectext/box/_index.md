---
title: Box()
second_title: Aspose.Slides for C++ API 参考
description: 将值类型装箱为 Object。针对枚举类型的实现。
type: docs
weight: 40
url: /zh/system/objectext/box/
---
## ObjectExt::Box(const T\&) 方法

将值类型装箱为 [Object](../../object/)。针对枚举类型的实现。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Enum](../../enum/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) 要装箱的值。 |

### 返回值

保持装箱值的智能指针。

## ObjectExt::Box(const T\&) 方法

将值类型装箱为 [Object](../../object/)。针对非枚举类型的实现。

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | 要装箱的值。 |

### 返回值

保持装箱值的智能指针。

## ObjectExt::Box(const T\&) 方法

[Nullable](../../nullable/) 类型装箱为 [Object](../../object/)。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | 要装箱的值。 |

### 返回值

保持装箱值的智能指针。

## ObjectExt::Box(const String\&) 方法

装箱字符串值。

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要装箱的值。 |

### 返回值

装箱后的值或 null（如果源字符串为 null）。

## 另见

* 类 [SmartPtr](../../smartptr/)
* 类 [Object](../../object/)
* 类 [ObjectExt](../)
* 类 [String](../../string/)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)