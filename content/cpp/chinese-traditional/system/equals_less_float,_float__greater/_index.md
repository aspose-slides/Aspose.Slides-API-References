---
title: Equals< float, float >()
second_title: Aspose.Slides for C++ API 參考文件
description: "針對單精度浮點值的特化。雖然 IEC 60559:1989 定義兩個浮點 NaN 總是比較為不相等，但 System.Object.Equals 的合約要求覆寫必須符合等價運算子的需求。因此，System.Double.Equals 與 System.Single.Equals 在比較兩個 NaN 時會傳回 True，而相等運算子在此情況下會傳回 False，符合標準規定。"
type: docs
weight: 2705
url: /zh-hant/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) 函式


單精度浮點值的特化。雖然 IEC 60559:1989 定義兩個浮點 NaN 總是比較為不相等，但 [System.Object.Equals](../object/equals/) 的合約要求覆寫必須符合等價運算子的需求。因此，System.Double.Equals 和 System.Single.Equals 在比較兩個 NaN 時會傳回 True，而等號運算子在此情況下會傳回 False，符合標準規定。

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | const **float**\& | 第一個比較項 |
| b | const **float**\& | 第二個比較項 |

### 傳回值

若兩個值皆為 NaN 或相等則傳回 True，否則傳回 false

## 參見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)