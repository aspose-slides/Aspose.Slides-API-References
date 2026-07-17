---
title: TieTuple()
second_title: Aspose.Slides for C++ API 参考
description: 创建与某些值绑定的元组。
type: docs
weight: 3017
url: /zh/system/tietuple/
---
## System::TieTuple(Args\&&...) 函数

创建与某些值绑定的元组。

```cpp
template<typename...> ValueTuple<Args...> System::TieTuple(Args &&... args)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Args | [Tuple](../tuple/) 成员类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | Args\&&... | [Tuple](../tuple/) 要绑定的值。 |

### 返回值

新创建的元组绑定到给定的值。

## 另见

* 类 [ValueTuple](../valuetuple/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)