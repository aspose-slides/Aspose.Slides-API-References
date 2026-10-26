---
title: invoke()
second_title: Aspose.Slides for C++ API 参考
description: 调用当前存在于委托集合中的所有委托。委托按添加到集合的顺序依次调用。该方法在委托执行期间会阻塞。
type: docs
weight: 222
url: /zh/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const 方法

调用当前存在于委托集合中的所有委托。委托的调用顺序与它们被添加到集合中的顺序相同。该方法在委托执行期间会阻塞。

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | ArgumentTypes... | 调用时传递给委托的参数 |

### 返回值

最后一个被调用委托的返回值

## 参见

* 类 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)