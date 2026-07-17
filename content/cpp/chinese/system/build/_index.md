---
title: Build()
second_title: Aspose.Slides for C++ API 参考
description: 构建一个直接拥有所有权的对象。
type: docs
weight: 2263
url: /zh/system/build/
---
## System::Build(Args\&&...) 函数

构建一个直接拥有所有权的对象。

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要构建的对象的类型 |
| Args | 对象构造的参数类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | Args\&&... | 转发给对象构造函数的参数 |

### 返回值

为直接对象构造配置的 ObjectBuilder

## 备注

[Object](../object/) 构造必须在调用 [Get()](../get/) 结束

## 另见

* Namespace [System](../)
* Library [Aspose.Slides](../../)