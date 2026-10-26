---
title: EnumParseHelper
second_title: Aspose.Slides for C++ API 參考
description: 提供將字串表示的列舉常數轉換為等價的 enum 值功能的輔助類別。
type: docs
weight: 1613
url: /zh-hant/system/enumparsehelper/
---
## EnumParseHelper 結構

提供將字串表示的列舉常數轉換為相對應列舉值的功能之輔助類別。

```cpp
template<class E,class G,class Guard>class EnumParseHelper
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| E | 類別方法所操作之列舉的類型 |
| G | 用於 [System::Enum](../enum/) 的第二個形式參數 |
| Guard | 用於選擇可用解析演算法的形式模板參數 |

## 方法

| 方法 | 說明 |
| --- | --- |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | 將指定的字串轉換為相等的列舉常數值 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)