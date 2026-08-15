---
title: SafeInvoke()
second_title: Aspose.Slides for C++ API 參考文件
description: 實作 '?.' 運算子的翻譯。
type: docs
weight: 2653
url: /zh-hant/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) 函式

實作 '?.' 運算子的翻譯。

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T0 | 表達式類型。 |
| T1 | 封裝 'WhenTrue' 表達式的 lambda 類型。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| expr | T0\&& | 表達式值。 |
| func | T1\&& | 'WhenTrue' 表達式綁定至函式物件。 |

### 傳回值

如果 expr 值不為 null，則回傳以其值作為第一個參數呼叫的 func；否則回傳 null。

## 另見

* 名稱空間 [System](../)
* 程式庫 [Aspose.Slides](../../)