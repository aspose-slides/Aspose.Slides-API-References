---
title: SafeInvoke()
second_title: Aspose.Slides C++ API 参考
description: 实现 '?.' 运算符的翻译。
type: docs
weight: 2614
url: /zh/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) 函数

实现 '?.' 运算符的翻译。

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T0 | 表达式类型。 |
| T1 | 封装 'WhenTrue' 表达式的 lambda 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expr | T0\&& | 表达式值。 |
| func | T1\&& | 绑定到仿函数的 'WhenTrue' 表达式。 |

### 返回值

如果 expr 的值不为 null，则返回调用 func 并以其值作为第一个参数的结果，否则返回 null。

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)