---
title: operator+()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値と、指定された Decimal オブジェクトが表す値の合計を表す Decimal クラスの新しいインスタンスを返します。
type: docs
weight: 2185
url: /ja/system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) 関数

指定された値と、指定された [Decimal](../decimal/) オブジェクトが表す値の合計を表す [Decimal](../decimal/) クラスの新しいインスタンスを返します。

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const T\& | 最初の加算項 |
| d | const [Decimal](../decimal/)\& | 第二の加算項を表す [Decimal](../decimal/) オブジェクトへの定数参照 |

### 戻り値

**x** と **d** が表す値の合計を表す [Decimal](../decimal/) クラスの新しいインスタンス。

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) 関数

右側デリゲートのすべてのコールバックを左側デリゲートのコールバックリストの末尾に接続します。

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | コールバックが追加されるデリゲート |
| rhv | MulticastDelegate\<T\> | 追加されるコールバックを持つデリゲート |

### 戻り値

左側の値のコールバックと右側のコールバックを順に含むデリゲートを返します。

## System::operator+(const T1\&, const Nullable\<T2\>\&) 関数

null 許容型と非 null 許容型の値を合計します。

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T1 | 左オペランドの型 |
| T2 | 右オペランドの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| some | const T1\& | 左オペランド |
| other | const [Nullable](../nullable/)\<T2\>\& | 右オペランド |

### 戻り値

合計結果。

## System::operator+(T\&, const String\&) 関数

[String](../string/) 連結。

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [String](../string/) リテラル型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | T\& | 文字列に連結するリテラル |
| right | const [String](../string/)\& | 連結する [String](../string/) |

### 戻り値

連結された文字列。

## System::operator+(T\&, const String\&) 関数

[String](../string/) 連結。

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | [String](../string/) ポインター型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | T\& | 文字列に連結する [String](../string/) ポインター |
| right | const [String](../string/)\& | 連結する [String](../string/) |

### 戻り値

連結された文字列。

## System::operator+(const char_t, const String\&) 関数

[String](../string/) 連結。

```cpp
String System::operator+(const char_t left, const String &right)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left | const char_t | 文字列に連結する文字 |
| right | const [String](../string/)\& | 連結する [String](../string/) |

### 戻り値

連結された文字列。

## 参照

* クラス [Decimal](../decimal/)
* クラス [Nullable](../nullable/)
* クラス [String](../string/)
* 構造体 [IsStringLiteral](../isstringliteral/)
* 構造体 [IsStringPointer](../isstringpointer/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)