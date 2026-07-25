---
title: CompareTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す日付と時刻の値と、DateTime クラスの指定されたインスタンスが表す日付と時刻の値を比較し、時間軸上での値の相対的な位置を示す値を返します。
type: docs
weight: 443
url: /ja/system/datetime/compareto/
---
## DateTime::CompareTo(DateTime) const メソッド

現在のオブジェクトが表す日付と時刻の値と、[DateTime](../) クラスの指定されたインスタンスが表す日付と時刻の値を比較し、時間軸上での値の相対的な位置を示す値を返します。

```cpp
constexpr int System::DateTime::CompareTo(DateTime value) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DateTime](../) | 現在のオブジェクトと比較するための、[DateTime](../) クラスのインスタンス |

### 戻り値

現在のオブジェクトが **value** によって表される値よりも早い時間を表す場合は 0 未満の値、両方のオブジェクトが表す値が同じ場合は 0、現在のオブジェクトが **value** によって表される値よりも遅い時間を表す場合は 0 より大きい値を返します。

## 参照

* クラス [DateTime](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)