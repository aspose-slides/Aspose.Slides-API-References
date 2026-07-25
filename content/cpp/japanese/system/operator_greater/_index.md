---
title: operator>()
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 2120
url: /ja/system/operator_greater/
---
## System::operator>(std::nullptr_t, DateTime) 関数




```cpp
constexpr bool System::operator>(std::nullptr_t, DateTime)
```
## System::operator>(std::nullptr_t, const DateTimeOffset\&) 関数




```cpp
constexpr bool System::operator>(std::nullptr_t, const DateTimeOffset &)
```
## System::operator>(std::nullptr_t, const Nullable\<T\>\&) 関数


常に false を返します。

```cpp
template<typename T> bool System::operator>(std::nullptr_t, const Nullable<T> &)
```
## System::operator>(const T1\&, const Nullable\<T2\>\&) 関数


指定された [Nullable](../nullable/) オブジェクトが表す値に [operator>()](./) を適用して、指定された値がその値より大きいかどうかを判断します。

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator>(const T1 &some, const Nullable<T2> &other)
```


### テンプレート パラメーター

| パラメータ | 説明 |
| --- | --- |
| T1 | 最初の比較対象の型 |
| T2 | 2番目の比較対象を表す [Nullable](../nullable/) オブジェクトの基底型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| some | const T1\& | 最初の比較対象として使用される値への const 参照 |
| other | const [Nullable](../nullable/)\<T2\>\& | 2番目の比較対象として使用される値を表す [Nullable](../nullable/) オブジェクトへの const 参照 |

### 戻り値

最初の比較対象が2番目の比較対象より大きい場合は True、そうでなければ false

## System::operator>(std::nullptr_t, TimeSpan) 関数




```cpp
constexpr bool System::operator>(std::nullptr_t, TimeSpan)
```

## 参照

* クラス [DateTime](../datetime/)
* クラス [DateTimeOffset](../datetimeoffset/)
* クラス [Nullable](../nullable/)
* クラス [TimeSpan](../timespan/)
* 構造体 [IsNullable](../isnullable/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)