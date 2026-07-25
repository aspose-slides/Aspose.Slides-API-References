---
title: Subtract()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す値から指定された時間間隔を減算した結果として得られる日付と時刻の値を表す DateTime クラスの新しいインスタンスを返します。
type: docs
weight: 326
url: /ja/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const method


現在のオブジェクトが表す値から指定された時間間隔を減算した結果となる日付と時刻の値を表す [DateTime](../) クラスの新しいインスタンスを返します。

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | 減算する時間間隔 |

### 戻り値

現在のオブジェクトが表す値から **duration** を減算した結果となる日付と時刻の値を表す [DateTime](../) クラスの新しいインスタンスを返します。

## DateTime::Subtract(DateTime) const method


[TimeSpan](../../timespan/) クラスのインスタンスを返します。このインスタンスは現在のオブジェクトと指定されたオブジェクトが表す日付と時刻の値間の時間間隔を表します。

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [DateTime](../) | 計算される間隔の片方の端点を示す [DateTime](../) クラスのインスタンス |

### 戻り値

現在のオブジェクトと **value** が表す日付と時刻の値間の時間間隔を表す [TimeSpan](../../timespan/) クラスのインスタンスを返します。

## 参照

* クラス [DateTime](../)
* クラス [TimeSpan](../../timespan/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)