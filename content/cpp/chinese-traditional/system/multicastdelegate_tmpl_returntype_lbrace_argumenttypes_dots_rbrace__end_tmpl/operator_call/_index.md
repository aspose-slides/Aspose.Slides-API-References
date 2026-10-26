---
title: operator()()
second_title: Aspose.Slides for C++ API 參考
description: 呼叫目前在 delegates 集合中的所有委派。委派會依照加入集合的順序被呼叫。operator 會在委派執行期間阻塞。
type: docs
weight: 235
url: /zh-hant/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const 方法

呼叫目前在 delegates 集合中的所有委派。委派會依照加入集合的順序被呼叫。operator 會在委派執行期間阻塞。

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| args | ArgumentTypes... | 傳遞給將被呼叫的委派的參數 |

### 返回值

最後被呼叫的委派的返回值

## 另見

* 類別 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)