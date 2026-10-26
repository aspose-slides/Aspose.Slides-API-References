---
title: UnknownIsNull()
second_title: Aspose.Slides for C++ API 参考
description: 检查未知类型对象是否为 nullptr。针对非标量类型的重载。
type: docs
weight: 144
url: /zh/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) 方法

检查未知类型对象是否为 nullptr。针对非标量类型的重载。

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T | [Object](../../object/) 用于检查。 |

### 返回值

如果 'obj == nullptr' 为真，则返回 True；否则返回 false。

## ObjectExt::UnknownIsNull(T) 方法

检查未知类型对象是否为 nullptr。针对标量类型的重载。

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T | [Object](../../object/) 用于检查。 |

### 返回值

始终返回 false。

## 参见

* 类 [ObjectExt](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)