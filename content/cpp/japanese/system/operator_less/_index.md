---
title: operator<()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 2094
url: /ja/system/operator_less/
---
## System::operator<(std::nullptr_t, DateTime) 関数




```cpp
constexpr bool System::operator<(std::nullptr_t, DateTime)
```

## System::operator<(std::nullptr_t, const DateTimeOffset\&) 関数




```cpp
constexpr bool System::operator<(std::nullptr_t, const DateTimeOffset &)
```

## System::operator<(std::nullptr_t, const Nullable\<T\>\&) 関数


常に false を返します。

```cpp
template<typename T> bool System::operator<(std::nullptr_t, const Nullable<T> &)
```

## System::operator<(const T1\&, const Nullable\<T2\>\&) 関数


指定された [Nullable](../nullable/) オブジェクトが表す値に対して [operator<()](./) を適用し、指定された値がその値より小さいかどうかを判定します。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator<(const T1 &some, const Nullable<T2> &other)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T1 | 最初の比較対象の値の型 |
| T2 | 2番目の比較対象の値を表す [Nullable](../nullable/) オブジェクトの基底型 |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | 最初の比較対象として使用される値への const 参照 |
| other | const [Nullable](../nullable/)\<T2\>\& | [Nullable](../nullable/) オブジェクト（その表す値が2番目の比較対象として使用される）への const 参照 |

### 戻り値

最初の比較対象が2番目の比較対象より小さい場合は true、そうでない場合は false

```cpp
constexpr bool System::operator<(std::nullptr_t, TimeSpan)
```

## 参照

* クラス [DateTime](../datetime/)
* クラス [DateTimeOffset](../datetimeoffset/)
* クラス [Nullable](../nullable/)
* クラス [TimeSpan](../timespan/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)