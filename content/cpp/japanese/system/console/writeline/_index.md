---
title: WriteLine()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在の行区切り文字を標準出力ストリームに出力します。
type: docs
weight: 14
url: /ja/system/console/writeline/
---
## Console::WriteLine() メソッド

現在の行区切り文字を標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine()
```

## Console::WriteLine(const SharedPtr\<T\>\&) メソッド

指定されたオブジェクトの文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
template<class T> static void System::Console::WriteLine(const SharedPtr<T> &object)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 出力するオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| object | const [SharedPtr](../../sharedptr/)\<T\>\& | [Object](../../object/) を出力 |

## Console::WriteLine(bool) メソッド

bool 値の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(bool value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **bool** | 出力する値 |

## Console::WriteLine(char_t) メソッド

指定された文字値を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(char_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 出力する値 |

## Console::WriteLine(const ArrayPtr\<char_t\>\&) メソッド

指定された文字配列の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 出力する配列 |

## Console::WriteLine(const Decimal\&) メソッド

[Decimal](../../decimal/) の値の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(const Decimal &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | 出力する値 |

## Console::WriteLine(double) メソッド

double 精度の浮動小数点値の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(double value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 出力する値 |

## Console::WriteLine(float) メソッド

単精度浮動小数点値の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(float value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 出力する値 |

## Console::WriteLine(int32_t) メソッド

32 ビット整数値の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(int32_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **int32_t** | 出力する値 |

## Console::WriteLine(int64_t) メソッド

64 ビット整数値の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(int64_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **int64_t** | 出力する値 |

## Console::WriteLine(const String\&) メソッド

指定された文字列オブジェクトを現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 出力する文字列オブジェクト |

## Console::WriteLine(const char_t *) メソッド

指定された C 文字列を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(const char_t *value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 出力する C文字列 |

## Console::WriteLine(const TypeInfo\&) メソッド

[TypeInfo](../../typeinfo/) の値の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(const TypeInfo &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 出力する値 |

## Console::WriteLine(uint32_t) メソッド

符号なし 32 ビット整数値の文字一覧表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(uint32_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint32_t** | 出力する値 |

## Console::WriteLine(uint64_t) メソッド

符号なし 64 ビット整数値の文字一覧表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(uint64_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint64_t** | 出力する値 |

## Console::WriteLine(const ArrayPtr\<char_t\>\&, int, int) メソッド

指定された文字配列の特定範囲の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(const ArrayPtr<char_t> &buffer, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 文字配列 |
| index | int | 出力範囲が開始する配列内のインデックス |
| count | int | 出力範囲の要素数 |

## Console::WriteLine(const Exception\&) メソッド

指定された Exception オブジェクトの文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
static void System::Console::WriteLine(const Exception &e)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| e | const [Exception](../../exception/)\& | 出力する値 |

## Console::WriteLine(const String\&, Args\&&...) メソッド

指定された書式に従ってフォーマットされた指定引数の文字列表現を現在の行区切り文字とともに標準出力ストリームに出力します。

```cpp
template<class...> static void System::Console::WriteLine(const String &format, Args &&... args)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| The | 出力する値の型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 文字列フォーマット |
| args | Args\&&... | 出力する値 |

## Console::WriteLine(const char *) メソッド

```cpp
static void System::Console::WriteLine(const char *)=delete
```

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* 型定義 [ArrayPtr](../../arrayptr/)
* 型定義 [Exception](../../exception/)
* クラス [Console](../)
* クラス [Decimal](../../decimal/)
* クラス [String](../../string/)
* クラス [TypeInfo](../../typeinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)