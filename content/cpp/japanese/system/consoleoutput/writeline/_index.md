---
title: WriteLine()
second_title: Aspose.Slides の C++ API リファレンス
description: 現在のオブジェクトが表す出力ストリームに、現在の行終端子を出力します。
type: docs
weight: 27
url: /ja/system/consoleoutput/writeline/
---
## ConsoleOutput::WriteLine() メソッド


現在のオブジェクトが表す出力ストリームに、現在の行終端子を出力します。

```cpp
void System::ConsoleOutput::WriteLine() override
```

## ConsoleOutput::WriteLine(const SharedPtr\<Object\>\&) メソッド


指定されたオブジェクトの文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(const SharedPtr<Object> &value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 出力するオブジェクト |

## ConsoleOutput::WriteLine(bool) メソッド


指定された bool 値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(bool value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **bool** | 出力するオブジェクト |

## ConsoleOutput::WriteLine(char_t) メソッド


指定された文字値に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(char_t value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 出力する値 |

## ConsoleOutput::WriteLine(Decimal) メソッド


[Decimal](../../decimal/) 値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(Decimal value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | 出力する値 |

## ConsoleOutput::WriteLine(double) メソッド


倍精度浮動小数点値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(double value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 出力する値 |

## ConsoleOutput::WriteLine(int) メソッド


32 ビット整数値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(int value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int | 出力する値 |

## ConsoleOutput::WriteLine(int64_t) メソッド


64 ビット整数値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(int64_t value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **int64_t** | 出力する値 |

## ConsoleOutput::WriteLine(float) メソッド


単精度浮動小数点値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(float value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 出力する値 |

## ConsoleOutput::WriteLine(const String\&) メソッド


指定された文字列オブジェクトに現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(const String &value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 出力する文字列オブジェクト |

## ConsoleOutput::WriteLine(uint32_t) メソッド


符号なし 32 ビット整数値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(uint32_t value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint32_t** | 出力する値 |

## ConsoleOutput::WriteLine(uint64_t) メソッド


符号なし 64 ビット整数値の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(uint64_t value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint64_t** | 出力する値 |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&) メソッド


指定された文字配列の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 出力する配列 |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) メソッド


指定された文字配列の一部の範囲の文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | 出力する値を含む配列 |
| index | **int32_t** | 出力する要素範囲の開始インデックス |
| count | **int32_t** | 出力する要素数 |

## ConsoleOutput::WriteLine(const char_t *) メソッド


指定された C 文字列に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(const char_t *value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 出力する C 文字列 |

## ConsoleOutput::WriteLine(const TypeInfo\&) メソッド


指定された [TypeInfo](../../typeinfo/) オブジェクトの文字列表現に現在の行終端子を付加して、現在のオブジェクトが表す出力ストリームに出力します。

```cpp
void System::ConsoleOutput::WriteLine(const TypeInfo &value) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | 出力する [TypeInfo](../../typeinfo/) オブジェクト |

## ConsoleOutput::WriteLine(const char *) メソッド




```cpp
void System::ConsoleOutput::WriteLine(const char *)=delete
```

## 関連項目

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* クラス [ConsoleOutput](../)
* クラス [Object](../../object/)
* クラス [Decimal](../../decimal/)
* クラス [String](../../string/)
* クラス [TypeInfo](../../typeinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)