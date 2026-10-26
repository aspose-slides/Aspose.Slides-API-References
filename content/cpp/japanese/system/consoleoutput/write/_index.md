---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された bool 値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。
type: docs
weight: 14
url: /ja/system/consoleoutput/write/
---
## ConsoleOutput::Write(bool) メソッド

指定された bool 値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(bool value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **bool** | 出力する値 |

## ConsoleOutput::Write(const SharedPtr\<Object\>\&) メソッド

指定されたオブジェクトの文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(const SharedPtr<Object> &value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 出力するオブジェクト |

## ConsoleOutput::Write(char_t) メソッド

指定された文字値を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(char_t value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 出力する値 |

## ConsoleOutput::Write(Decimal) メソッド

[Decimal](../../decimal/) 値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(Decimal value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | 出力する値 |

## ConsoleOutput::Write(double) メソッド

倍精度浮動小数点値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(double value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 出力する値 |

## ConsoleOutput::Write(int32_t) メソッド

32 ビット整数値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(int32_t value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **int32_t** | 出力する値 |

## ConsoleOutput::Write(int64_t) メソッド

64 ビット整数値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(int64_t value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **int64_t** | 出力する値 |

## ConsoleOutput::Write(float) メソッド

単精度浮動小数点値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(float value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 出力する値 |

## ConsoleOutput::Write(const String\&) メソッド

指定された文字列オブジェクトを、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(const String &value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 出力する文字列オブジェクト |

## ConsoleOutput::Write(uint32_t) メソッド

符号なし 32 ビット整数値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(uint32_t value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint32_t** | 出力する値 |

## ConsoleOutput::Write(uint64_t) メソッド

符号なし 64 ビット整数値の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(uint64_t value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint64_t** | 出力する値 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&) メソッド

指定された文字配列の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 出力する配列 |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) メソッド

指定された文字配列の範囲の文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 出力する値を含む配列 |
| index | **int32_t** | 出力範囲の開始インデックス |
| count | **int32_t** | 出力範囲の要素数 |

## ConsoleOutput::Write(const char_t *) メソッド

指定された C 文字列を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(const char_t *value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 出力する C 文字列 |

## ConsoleOutput::Write(const TypeInfo\&) メソッド

指定された [TypeInfo](../../typeinfo/) オブジェクトの文字列表現を、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::Write(const TypeInfo &value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 出力する [TypeInfo](../../typeinfo/) オブジェクト |

## ConsoleOutput::Write(const char *) メソッド




```cpp
void System::ConsoleOutput::Write(const char *)=delete
```

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [ConsoleOutput](../)
* Class [Object](../../object/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)