---
title: RoundImpl()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を、指定された小数桁数で最も近い値に丸めます。パラメータは、指定された値が 2 つの最も近い数値に同等に近い場合の関数の動作を指定します。
type: docs
weight: 287
url: /ja/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) メソッド

指定された value を、指定された小数桁数で最も近い値に丸めます。パラメータは、指定された value が 2 つの最も近い数値に同等に近い場合の関数の動作を指定します。

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **float** | value を丸めるための値 |
| digits | int | 丸められた value の小数桁数 |
| mode | [MidpointRounding](../../midpointrounding/) | **value** が 2 つの最も近い数値に同等に近い場合の丸め処理方法を指定します |

### 戻り値

指定された桁数で **value** に最も近い数値

## 参照

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)