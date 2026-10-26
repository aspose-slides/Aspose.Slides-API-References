---
title: operator()()
second_title: Aspose.Slides for C++ API 参考
description: 调用委托集合中当前存在的所有委托。委托按照它们被添加到集合中的顺序进行调用。操作符在委托执行期间会阻塞。
type: docs
weight: 235
url: /zh/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const 方法


调用当前在委托集合中存在的所有委托。委托按照它们被添加到集合中的顺序进行调用。操作符在委托执行期间会阻塞。

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | ArgumentTypes... | 传递给要调用的委托的参数 |

### 返回值

最后一个被调用的委托的返回值

## 另请参阅

* 类 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)