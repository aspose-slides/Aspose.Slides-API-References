---
title: With()
second_title: Aspose.Slides for C++ API 参考
description: 克隆引用记录并对其应用初始化仿函数。
type: docs
weight: 2575
url: /zh/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) 函数

克隆引用记录并对其应用初始化仿函数。

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要克隆的记录类型。 |
| A | 初始化仿函数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | 用于克隆并初始化对象的共享指针。 |
| initializer | const A\& | 应用于记录克隆的初始化仿函数。 |

### 返回值

指向克隆记录的共享指针。

## System::With(const T\&, const A\&) 函数

复制结构体记录并对其应用初始化仿函数。

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要复制的记录类型。 |
| A | 初始化仿函数类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| record | const T\& | 要复制并初始化的记录。 |
| initializer | const A\& | 应用于记录副本的初始化仿函数。 |

### 返回值

已复制的记录。

## 另请参见

* 类型定义 [SharedPtr](../sharedptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)