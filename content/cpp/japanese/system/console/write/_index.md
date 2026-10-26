---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたオブジェクトの文字列表現を標準出力ストリームに出力します。
type: docs
weight: 1
url: /ja/system/console/write/
---
## Console::Write(const SharedPtr\<T\>\&) メソッド

指定されたオブジェクトの文字列表現を標準出力ストリームに出力します。

```cpp
template<class T> static void System::Console::Write(const SharedPtr<T> &object)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 出力するオブジェクトの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) を出力 |

## Console::Write(bool) メソッド

bool 値の文字一覧表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(bool value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **bool** | 出力する値 |

## Console::Write(char_t) メソッド

指定された文字値を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(char_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 出力する値 |

## Console::Write(const ArrayPtr\<char_t\>\&) メソッド

指定された文字配列の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 出力する配列 |

## Console::Write(const Decimal\&) メソッド

[Decimal](../../decimal/) 値の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(const Decimal &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 出力する値 |

## Console::Write(double) メソッド

倍精度浮動小数点値の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(double value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 出力する値 |

## Console::Write(float) メソッド

単精度浮動小数点値の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(float value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 出力する値 |

## Console::Write(int32_t) メソッド

32 ビット整数値の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(int32_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **int32_t** | 出力する値 |

## Console::Write(int64_t) メソッド

64 ビット整数値の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(int64_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **int64_t** | 出力する値 |

## Console::Write(const String\&) メソッド

指定された文字列オブジェクトを標準出力ストリームに出力します。

```cpp
static void System::Console::Write(const String &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 出力する文字列オブジェクト |

## Console::Write(const char_t *) メソッド

指定された C 文字列を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(const char_t *value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 出力する C 文字列 |

## Console::Write(const TypeInfo\&) メソッド

[TypeInfo](../../typeinfo/) 値の文字一覧表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(const TypeInfo &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 出力する値 |

## Console::Write(uint32_t) メソッド

符号なし 32 ビット整数値の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(uint32_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint32_t** | 出力する値 |

## Console::Write(uint64_t) メソッド

符号なし 64 ビット整数値の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(uint64_t value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | **uint64_t** | 出力する値 |

## Console::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) メソッド

指定された文字配列の指定された範囲の文字列表現を標準出力ストリームに出力します。

```cpp
static void System::Console::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 文字配列 |
| index | **int32_t** | 出力範囲の開始インデックス |
| count | **int32_t** | 出力範囲の要素数 |

## Console::Write(const String\&, Args\&&...) メソッド

指定された書式に従ってフォーマットされた引数の文字列表現を標準出力ストリームに出力します。

```cpp
template<class...> static void System::Console::Write(const String &format, Args &&... args)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| The | 出力する値の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 文字列書式 |
| args | Args\&&... | 出力する値 |

## Console::Write(const char *) メソッド




```cpp
static void System::Console::Write(const char *)=delete
```

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Console](../)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)