---
title: CoalesceInternal()
second_title: Aspose.Slides for C++ API 參考文件
description: 非可為 null 類型的 '??' 運算子轉換實作。當 RT2 可轉換為 RT1 時的重載。
type: docs
weight: 157
url: /zh-hant/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) 方法

實作非可為 null 類型的 '??' 運算子轉換。當 RT2 可轉換為 RT1 時的重載。

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### 模板參數

| Parameter | Description |
| --- | --- |
| T0 | LHS 值類型。 |
| T1 | 封裝 RHS 表達式的 lambda 類型。 |

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | RT1 | LHS 值。 |
| func | F | RHS 表達式。 |

### 返回值

如果 LHS 值不為 null，則返回 LHS；否則計算 RHS 表達式並返回結果。

## 另見

* 類別 [ObjectExt](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)