---
title: invoke()
second_title: Aspose.Slides for C++ API 參考
description: 調用目前存在於 delegates 集合中的所有委託。委託會按照它們被添加到集合中的相同順序被調用。該方法會在委託執行期間阻塞。
type: docs
weight: 222
url: /zh-hant/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const 方法

調用當前在 delegates 集合中存在的所有委託。委託會按照它們被添加到集合中的相同順序被調用。該方法會在委託執行期間阻塞。

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| args | ArgumentTypes... | 傳遞給要調用的委託的參數 |

### 返回值

最後一次被調用的委託的返回值

## 另請參閱

* 類別 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)