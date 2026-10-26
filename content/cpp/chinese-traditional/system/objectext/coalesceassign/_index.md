---
title: CoalesceAssign()
second_title: Aspose.Slides for C++ API 參考文件
description: 實作 '??=' 運算子翻譯。
type: docs
weight: 183
url: /zh-hant/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) 方法

Implementation of '??=' operator translation.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T0 | LHS 值類型。 |
| T1 | 封裝 RHS 表達式的 lambda 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | T0\& | LHS 值。 |
| func | T1 | RHS 表達式。 |

### 返回值

如果 LHS 值不為 null，則回傳 LHS，否則計算 RHS 表達式並回傳結果。

## 另請參閱

* 類別 [ObjectExt](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)