---
title: WriteLine()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームに改行文字を書き込みます。
type: docs
weight: 118
url: /ja/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() メソッド

ストリームに改行文字を書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) メソッド

指定されたオブジェクトの文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 書き込むオブジェクト |

## TextWriter::WriteLine(bool) メソッド

指定されたブール値の文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **bool** | 書き込む値 |

## TextWriter::WriteLine(char_t) メソッド

指定された文字を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 書き込む値 |

## TextWriter::WriteLine(Decimal) メソッド

指定された [Decimal](../../../system/decimal/) オブジェクトの文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | 書き込むオブジェクト |

## TextWriter::WriteLine(double) メソッド

指定された倍精度浮動小数点値の文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 書き込む値 |

## TextWriter::WriteLine(int) メソッド

指定された 32 ビット整数値の文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int | 書き込む値 |

## TextWriter::WriteLine(int64_t) メソッド

指定された 64 ビット整数値の文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **int64_t** | 書き込む値 |

## TextWriter::WriteLine(float) メソッド

指定された単精度浮動小数点値の文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 書き込む値 |

## TextWriter::WriteLine(const String\&) メソッド

指定された文字列を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 書き込む文字列 |

## TextWriter::WriteLine(uint32_t) メソッド

指定された符号なし 32 ビット整数値の文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint32_t** | 書き込む値 |

## TextWriter::WriteLine(uint64_t) メソッド

指定された符号なし 64 ビット整数値の文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint64_t** | 書き込む値 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) メソッド

指定された配列のすべての文字を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) メソッド

指定された文字配列から UTF-16 文字の指定サブレンジを書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |
| index | **int32_t** | **buffer** 内でサブレンジの開始位置を示す 0 ベースのインデックス |
| count | **int32_t** | 書き込むサブレンジの文字数。-1 を指定すると **buffer** 配列の末尾までが対象となります |

## TextWriter::WriteLine(const char_t *) メソッド

指定された C 文字列を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 書き込む C 文字列 |

## TextWriter::WriteLine(const TypeInfo\&) メソッド

指定された [TypeInfo](../../../system/typeinfo/) オブジェクトの文字列表現を書き込み、続けて改行文字をストリームに書き込みます。

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | 書き込むオブジェクト |

## TextWriter::WriteLine(const String\&, const TArgs\&...) メソッド

指定された書式に従って指定された値をフォーマットし、続けて改行文字を書き込みます。

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| TArgs | 書き込む値の型リスト |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | 文字列書式 |
| args | const TArgs\&... | 書き込む値 |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Class [Object](../../../system/object/)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)