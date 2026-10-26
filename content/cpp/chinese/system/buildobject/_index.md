---
title: BuildObject()
second_title: Aspose.Slides for C++ API 参考
description: 使用共享所有权构建对象。
type: docs
weight: 2224
url: /zh/system/buildobject/
---
## System::BuildObject(Args\&&...) 函数

使用共享所有权构建对象。

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| T | 要构建的对象类型 |
| Args | 对象构造的参数类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| args | Args\&&... | 转发给对象构造函数的参数 |

### 返回值

已配置用于共享指针构造的 ObjectBuilder

## 备注

创建一个 SharedPtr<T> 并返回其构建器
[Object](../object/) 构造必须以 [Get()](../get/) 调用结束

## 另见

* 类型定义 [SharedPtr](../sharedptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)