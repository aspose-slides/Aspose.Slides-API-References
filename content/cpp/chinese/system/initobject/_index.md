---
title: InitObject()
second_title: Aspose.Slides for C++ API 参考
description: 开始对具有共享所有权的对象进行初始化。
type: docs
weight: 2237
url: /zh/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) 函数

开始对具有共享所有权的对象进行初始化。

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要初始化的对象类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) 用于初始化 |

### 返回值

为共享指针构造配置的 ObjectBuilder

## 备注

[Object](../object/) 初始化必须以 [Get()](../get/) 调用结束

## 另见

* 类型定义 [SharedPtr](../sharedptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)