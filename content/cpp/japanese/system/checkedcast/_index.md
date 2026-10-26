---
title: CheckedCast()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値が型 TTo の値の範囲に入っているかどうかを判断し、入っている場合はそれを型 TTo にキャストします。
type: docs
weight: 2796
url: /ja/system/checkedcast/
---
## System::CheckedCast(TFrom) 関数

指定された値が型 **TTo** の値の範囲に入っているかどうかを判断し、入っている場合はそれを型 **TTo** にキャストします。

```cpp
template<typename TTo,typename TFrom> TTo System::CheckedCast(TFrom value)
```

### テンプレートパラメータ

| Parameter | Description |
| --- | --- |
| TTo | 指定された値がキャストされる型 |
| TFrom | 指定された値の型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | キャスト対象の値 |

### 戻り値

**value** に相当する型 **TTo** の値

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)