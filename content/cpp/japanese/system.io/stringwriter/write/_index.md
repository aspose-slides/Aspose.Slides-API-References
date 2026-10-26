---
title: Write()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字をストリームに書き込みます。
type: docs
weight: 40
url: /ja/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) メソッド

指定された文字をストリームに書き込みます。

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char_t | 書き込む値 |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) メソッド

指定された文字配列から指定された文字のサブレンジをストリームに書き込みます。

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | 書き込む文字を含む配列 |
| index | **int32_t** | 書き込むサブレンジが開始する **buffer** 内の 0 基準インデックス |
| count | **int32_t** | 書き込むサブレンジ内の文字数 |

## StringWriter::Write(const String\&) メソッド

指定された文字列をストリームに書き込みます。

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | 書き込む文字列 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [StringWriter](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)