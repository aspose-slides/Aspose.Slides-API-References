---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された符号なし 8 ビット整数値を出力ストリームに書き込みます。
type: docs
weight: 92
url: /ja/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) メソッド

指定された unsigned 8 ビット整数値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint8_t** | 書き込む値 |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) メソッド

指定されたバイト配列から指定されたバイトのサブレンジを出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | 書き込むバイトを含む配列 |
| index | int | 書き込みサブレンジが開始する **buffer** 内の 0 ベースのインデックス |
| count | int | 書き込むサブレンジ内の要素数。-1 はサブレンジが **buffer** 配列の終端まで続くことを示します |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) メソッド

指定された文字配列から指定された UTF-16 文字のサブレンジを出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |
| index | int | 書き込みサブレンジが開始する **buffer** 内の 0 ベースのインデックス |
| count | int | 書き込むサブレンジ内の文字数。-1 はサブレンジが **buffer** 配列の終端まで続くことを示します |

## BinaryWriter::Write(bool) メソッド

**value** が true の場合は 0、false の場合は 1 の単一バイトを出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **bool** | 出力ストリームに書き込むバイト値を指定するブール値 |

## BinaryWriter::Write(char16_t) メソッド

指定された 16 ビット幅の文字値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char16_t | 書き込む値 |

## BinaryWriter::Write(int16_t) メソッド

指定された 16 ビット整数値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **int16_t** | 書き込む値 |

## BinaryWriter::Write(int) メソッド

指定された 32 ビット整数値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int | 書き込む値 |

## BinaryWriter::Write(int64_t) メソッド

指定された 64 ビット整数値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **int64_t** | 書き込む値 |

## BinaryWriter::Write(uint16_t) メソッド

指定された符号なし 16 ビット整数値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint16_t** | 書き込む値 |

## BinaryWriter::Write(uint32_t) メソッド

指定された符号なし 32 ビット整数値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint32_t** | 書き込む値 |

## BinaryWriter::Write(uint64_t) メソッド

指定された符号なし 64 ビット整数値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **uint64_t** | 書き込む値 |

## BinaryWriter::Write(float) メソッド

指定された単精度浮動小数点値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **float** | 書き込む値 |

## BinaryWriter::Write(double) メソッド

指定された倍精度浮動小数点値を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | **double** | 書き込む値 |

## BinaryWriter::Write(const Decimal\&) メソッド

指定された [Decimal](../../../system/decimal/) のバイト表現を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | 書き込む値 |

## BinaryWriter::Write(const String\&) メソッド

現在のエンコーディングで長さプレフィックス付き文字列を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 書き込む文字列 |

## BinaryWriter::Write(const char_t *) メソッド

現在のエンコーディングで長さプレフィックス付き文字列を出力ストリームに書き込みます。

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 書き込む C 文字列 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [BinaryWriter](../)
* クラス [Decimal](../../../system/decimal/)
* クラス [String](../../../system/string/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)