---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたオブジェクトの文字列表現をストリームに書き込みます。
type: docs
weight: 105
url: /ja/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) method


指定されたオブジェクトの文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 書き込むオブジェクト |

## TextWriter::Write(bool) method


指定されたブール値の文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **bool** | 書き込む値 |

## TextWriter::Write(char_t) method


指定された文字を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 書き込む値 |

## TextWriter::Write(Decimal) method


指定された[Decimal](../../../system/decimal/)オブジェクトの文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 書き込むオブジェクト |

## TextWriter::Write(double) method


指定された倍精度浮動小数点値の文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 書き込む値 |

## TextWriter::Write(int) method


指定された32ビット整数値の文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | 書き込む値 |

## TextWriter::Write(int64_t) method


指定された64ビット整数値の文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **int64_t** | 書き込む値 |

## TextWriter::Write(float) method


指定された単精度浮動小数点値の文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 書き込む値 |

## TextWriter::Write(const String\&) method


指定された文字列を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 書き込む文字列 |

## TextWriter::Write(uint32_t) method


指定された符号なし32ビット整数値の文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint32_t** | 書き込む値 |

## TextWriter::Write(uint64_t) method


指定された符号なし64ビット整数値の文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint64_t** | 書き込む値 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) method


指定された配列からすべての文字を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) method


指定された文字配列からUTF-16文字の指定されたサブレンジを書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |
| index | **int32_t** | **buffer** 内でサブレンジの開始位置を示す 0 ベースのインデックス |
| count | **int32_t** | 書き込むサブレンジ内の文字数。-1 を指定すると **buffer** 配列の末端までがサブレンジとなります |

## TextWriter::Write(const char_t *) method


指定されたC文字列を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 書き込むC文字列 |

## TextWriter::Write(const TypeInfo\&) method


指定された[TypeInfo](../../../system/typeinfo/)オブジェクトの文字列表現を書き込みます。

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 書き込むオブジェクト |

## TextWriter::Write(const String\&, const TArgs\&...) method


指定されたフォーマットに従ってフォーマットされた指定された値を書き込みます。

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TArgs | 書き込む値の型リスト |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 文字列フォーマット |
| args | const TArgs\&... | 書き込む値 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)