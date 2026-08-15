---
title: RoundImpl()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的值四捨五入到最近的值，保留指定的小數位數。若指定的值與兩個最近的數字等距，則有參數決定函式的行為。
type: docs
weight: 287
url: /zh-hant/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) 方法

將指定的值四捨五入到最近的值，保留指定的小數位數。若指定的值與兩個最近的數字等距，則有參數決定函式的行為。

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **float** | 要四捨五入的 value |
| digits | int | 已四捨五入的值中小數位的數量 |
| mode | [MidpointRounding](../../midpointrounding/) | 指定如果 value 與兩個最近的數字等距時，如何執行四捨五入。 |

### 回傳值

最接近 value 且具有指定小數位數的數字

## 另請參閱

* 列舉 [MidpointRounding](../../midpointrounding/)
* 結構 [MathF](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)