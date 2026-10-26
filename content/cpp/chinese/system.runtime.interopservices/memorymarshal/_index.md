---
title: MemoryMarshal
second_title: Aspose.Slides for C++ API 参考
description: 提供内存编组实现。仅为兼容已翻译的代码而存在，因为 C++ 端不支持托管代码。这是一个没有实例服务的静态类型。无论何种方式，都不应创建其实例。
type: docs
weight: 27
url: /zh/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal 类


提供内存编组实现。仅为兼容已翻译的代码而存在，因为 C++ 端不支持托管代码。这是一个没有实例服务的静态类型。无论何种方式，都不应创建其实例。

```cpp
class MemoryMarshal
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | 将一种原始类型 T 的 [Span](../../system/span/) 转换为字节的 [Span](../../system/span/)。 |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | 将一种原始类型 TFrom 的 [Span](../../system/span/) 转换为另一种原始类型 TTo。 |
## 参见

* 命名空间 [System::Runtime::InteropServices](../)
* 库 [Aspose.Slides](../../)