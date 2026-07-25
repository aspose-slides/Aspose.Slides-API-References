---
title: WriteLine()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームに改行文字を書き込みます。
type: docs
weight: 92
url: /ja/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() メソッド

ストリームに改行文字を書き込みます。

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) メソッド

指定された文字列を書き込み、続いて改行文字を書き込みます。

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 書き込む文字列 |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) メソッド

指定されたオブジェクトの文字列表現を書き込み、続いて改行文字を書き込みます。

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 書き込むオブジェクト |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) メソッド

指定された配列からすべての文字を書き込み、続いて改行文字を書き込みます。

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) メソッド

指定された文字配列から UTF-16 文字のサブレンジを書き込み、続いて改行文字を書き込みます。

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |
| index | **int32_t** | 書き込むサブレンジの開始位置を示す **buffer** 内の 0 基準インデックス |
| count | **int32_t** | 書き込むサブレンジの文字数。-1 を指定すると、サブレンジは **buffer** 配列の末尾までになります |

## StreamWriter::WriteLine(const char_t *) メソッド

指定された c-string を書き込み、続いて改行文字を書き込みます。

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | const char_t * | 書き込む c-string |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) メソッド

指定されたオブジェクトの文字列表現を書き込み、続いて改行文字を書き込みます。

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | オブジェクトの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | 書き込むオブジェクト |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [StreamWriter](../)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)