---
title: operator-()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す値から指定された時間間隔を減算した結果となる日時値を表す、DateTime クラスの新しいインスタンスを返します。
type: docs
weight: 651
url: /ja/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const method

現在のオブジェクトが表す値から指定された時間間隔を減算した結果となる日時値を表す、[DateTime](../) クラスの新しいインスタンスを返します。

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 減算する時間間隔 |

### 戻り値

現在のオブジェクトが表す値から **value** を減算した結果となる日時値を表す、[DateTime](../) クラスの新しいインスタンスを返します。

## DateTime::operator-(DateTime) const method

現在のオブジェクトと指定されたオブジェクトが表す日時値間の時間間隔を表す、[TimeSpan](../../timespan/) クラスのインスタンスを返します。

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DateTime](../) | [DateTime](../) クラスのインスタンスで、計算対象の間隔の一端を示します |

### 戻り値

現在のオブジェクトと **value** が表す日時値間の時間間隔を表す、[TimeSpan](../../timespan/) クラスのインスタンスを返します。

## 参照

* クラス [DateTime](../)
* クラス [TimeSpan](../../timespan/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)