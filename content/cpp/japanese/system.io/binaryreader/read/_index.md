---
title: Read()
second_title: Aspose.Slides for C++ API リファレンス
description: 入力ストリームから単一文字を読み取ります。
type: docs
weight: 66
url: /ja/system.io/binaryreader/read/
---
## BinaryReader::Read() メソッド

入力ストリームから単一文字を読み取ります。

```cpp
virtual int System::IO::BinaryReader::Read()
```

### 戻り値

UTF-16 エンコーディングでエンコードされた文字を読み取ります。UTF-16 エンコーディングで文字が 2 つのコードポイントで表現されている場合、上位サロゲートのみが返されます。

## BinaryReader::Read(ArrayPtr\<uint8_t\>, int, int) メソッド

入力ストリームから指定されたバイト数を読み取り、指定されたバイト配列に書き込みます。

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<uint8_t> buffer, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 読み取ったバイトを書き込むバイト配列 |
| index | int | 書き込みを開始する **buffer** 内の 0 基準の位置 |
| count | int | 読み取るバイト数 |

### 戻り値

読み取られたバイト数

## BinaryReader::Read(ArrayPtr\<char_t\>, int, int) メソッド

入力ストリームから指定された文字数を読み取り、UTF-16 エンコーディングに変換し、指定された位置から開始する指定された文字配列に変換後の UTF-16 文字を書き込みます。

```cpp
virtual int System::IO::BinaryReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 入力ストリームから読み取った文字を書き込む UTF-16 文字配列 |
| index | int | **buffer** 内の書き込みを開始する 0 基準のインデックス |
| count | int | ストリームから読み取る文字数 |

### 戻り値

入力ストリームから読み取られた文字数

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [BinaryReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)