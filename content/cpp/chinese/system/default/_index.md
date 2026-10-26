---
title: Default()
second_title: Aspose.Slides C++ API 参考
description: 返回该异常类型的唯一默认构造实例的引用。
type: docs
weight: 2198
url: /zh/system/default/
---
## System::Default() 函数

返回该异常类型的唯一默认构造实例的引用。

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要返回其实例的类型 |

## System::Default() 函数

返回该非异常类型的唯一默认构造实例的引用。

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要返回其实例的类型 |

## 另请参见

* 结构体 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)