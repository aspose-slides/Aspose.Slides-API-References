---
title: operator-()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す値から指定された時間間隔を減算した結果となる日付と時刻の値を表す DateTimeOffset クラスの新しいインスタンスを返します。
type: docs
weight: 521
url: /ja/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const メソッド


現在のオブジェクトが表す値から指定された時間間隔を減算した結果となる日付と時刻の値を表す [DateTimeOffset](../) クラスの新しいインスタンスを返します。

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | 減算する時間間隔 |

### 戻り値

[DateTimeOffset](../) クラスの新しいインスタンスで、現在のオブジェクトが表す値から **value** を減算した結果となる日付と時刻の値を表します。

## DateTimeOffset::operator-(const DateTimeOffset\&) const メソッド


現在のオブジェクトと指定されたオブジェクトが表す日付と時刻の値の間の時間間隔を表す [TimeSpan](../../timespan/) クラスのインスタンスを返します。

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | [DateTime](../../datetime/) クラスのインスタンスで、計算される間隔の一端を示します |

### 戻り値

[TimeSpan](../../timespan/) クラスのインスタンスで、現在のオブジェクトと **other** が表す日付と時刻の値の間の時間間隔を表します。

## 参照

* クラス [DateTimeOffset](../)
* クラス [TimeSpan](../../timespan/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)