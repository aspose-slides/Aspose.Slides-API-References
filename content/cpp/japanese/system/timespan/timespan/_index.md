---
title: TimeSpan()
second_title: Aspose.Slides for C++ API リファレンス
description: ゼロ時間間隔を表す TimeSpan オブジェクトを構築します。
type: docs
weight: 1
url: /ja/system/timespan/timespan/
---
## TimeSpan::TimeSpan() コンストラクタ

ゼロ時間間隔を表す[TimeSpan](../)オブジェクトを構築します。

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) コンストラクタ

[TimeSpan](../)クラスのインスタンスを構築し、指定された時間間隔を表します。

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ticks | **int64_t** | 構築されるインスタンスが表す時間間隔を、100 ナノ秒単位の間隔数で表したもの。 |

## TimeSpan::TimeSpan(int, int, int) コンストラクタ

[TimeSpan](../)クラスのインスタンスを構築し、指定された時間数・分数・秒数の合計に等しい時間間隔を表します。

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hours | int | 構築されるインスタンスが表す時間間隔の時間成分の時間数。 |
| minutes | int | 構築されるインスタンスが表す時間間隔の分成分の分数。 |
| seconds | int | 構築されるインスタンスが表す時間間隔の秒成分の秒数。 |

## TimeSpan::TimeSpan(int, int, int, int, int) コンストラクタ

[TimeSpan](../)クラスのインスタンスを構築し、指定された日数、時間、分、秒、ミリ秒の合計に等しい時間間隔を表します。

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| days | int | 構築されるインスタンスが表す時間間隔の日成分の日数。 |
| hours | int | 構築されるインスタンスが表す時間間隔の時間成分の時間数。 |
| minutes | int | 構築されるインスタンスが表す時間間隔の分成分の分数。 |
| seconds | int | 構築されるインスタンスが表す時間間隔の秒成分の秒数。 |
| milliseconds | int | 構築されるインスタンスが表す時間間隔のミリ秒成分のミリ秒数。 |

## TimeSpan::TimeSpan(const TimeSpan\&) コンストラクタ

指定された[TimeSpan](../)オブジェクトが表す時間間隔と等しい時間間隔を表す[TimeSpan](../)オブジェクトを構築します。

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## 参照

* クラス [TimeSpan](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)