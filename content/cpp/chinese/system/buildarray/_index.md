---
title: BuildArray()
second_title: Aspose.Slides for C++ API 参考
description: 构建数组。
type: docs
weight: 2250
url: /zh/system/buildarray/
---
## System::BuildArray() 函数

构建数组。

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要构建的数组的元素类型 |

### 返回值

配置用于数组构建的 ObjectBuilder
## 备注

创建一个 ArrayPtr<T> 并返回其构建器
[Object](../object/) 构造必须使用 [Get()](../get/) 调用来完成

## 参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)