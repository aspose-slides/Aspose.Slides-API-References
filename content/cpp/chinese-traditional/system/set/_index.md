---
title: Set()
second_title: Aspose.Slides C++ API 參考
description: 實作 'var' 模式的翻譯。
type: docs
weight: 2380
url: /zh-hant/system/set/
---
## System::Set(ExpressionT\&, const ExpressionT\&) 函式


Implements 'var' pattern translation.

```cpp
template<class ExpressionT> bool System::Set(ExpressionT &var, const ExpressionT &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| ExpressionT | 變數類型。 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| var | ExpressionT\& | 指向要被初始化的變數的參考。 |
| value | const ExpressionT\& | 要指派給變數的值。 |

### Return Value

永遠為 true（此模式永遠命中）。

## See Also

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)