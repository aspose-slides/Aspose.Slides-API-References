---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字をストリームに書き込みます。
type: docs
weight: 79
url: /ja/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) メソッド

指定された文字をストリームに書き込みます。

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 書き込む文字 |

## StreamWriter::Write(const String\&) メソッド

指定された文字列をストリームに書き込みます。

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 書き込む文字列 |

## StreamWriter::Write(const SharedPtr\<Object\>\&) メソッド

指定されたオブジェクトの文字列表現を書き込みます。

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 書き込むオブジェクト |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) メソッド

指定された配列からすべての文字を書き込みます。

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) メソッド

指定された文字配列からUTF-16文字のサブレンジを書き込みます。

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |
| index | **int32_t** | **buffer** 内のサブレンジ開始位置を示す0ベースインデックス |
| count | **int32_t** | 書き込むサブレンジ内の文字数。-1 を指定すると **buffer** 配列の末尾までが対象になります |

## StreamWriter::Write(const char_t *) メソッド

指定されたC文字列を書き込みます。

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const char_t * | 書き込むC文字列 |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) メソッド

指定されたオブジェクトの文字列表現を書き込みます。

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | 書き込むオブジェクト |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [StreamWriter](../)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)