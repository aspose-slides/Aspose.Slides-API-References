---
title: operator-()
second_title: Aspose.Slides for C++ API リファレンス
description: 2つの曜日間の日数を計算します。
type: docs
weight: 2172
url: /ja/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) 関数

2つの曜日間の日数を計算します。

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | 被減数 |
| b | [DayOfWeek](../dayofweek/) | 減数 |

### 戻り値

weekday **a** と **b** の間の日数です; 戻り値は *goes* が後になる場合は負の数になります。

## System::operator-(const T\&, const Decimal\&) 関数

指定された値から、指定された [Decimal](../decimal/) オブジェクトが表す値を減算した結果の値を表す、[Decimal](../decimal/) クラスの新しいインスタンスを返します。

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | const T\& | 減算される値 |
| d | const [Decimal](../decimal/)\& | [Decimal](../decimal/) オブジェクト（減算される値を表す） |

### 戻り値

[Decimal](../decimal/) クラスの新しいインスタンスで、**x** から **d** が表す値を減算した結果の値を表します。

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 関数

右側デリゲートのすべてのコールバックを、左側デリゲートのコールバックリストの末尾から切り離します。

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | コールバックが削除される左側デリゲート。 |
| rhv | MulticastDelegate\<T\> | コールバックが削除される右側デリゲート。 |

### 戻り値

左側のデリゲートのコールバックを含み、右側のデリゲートのコールバックを除いたデリゲートを返します。

## System::operator-(const T1\&, const Nullable\<T2\>\&) 関数

非NULL値とNULL可能値を減算します。

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T1 | 左オペランドの型。 |
| T2 | 右オペランドの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| some | const T1\& | 左オペランド。 |
| other | const [Nullable](../nullable/)\<T2\>\& | 右オペランド。 |

### 戻り値

減算結果。

## 参照

* 列挙型 [DayOfWeek](../dayofweek/)
* クラス [Decimal](../decimal/)
* クラス [Nullable](../nullable/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)