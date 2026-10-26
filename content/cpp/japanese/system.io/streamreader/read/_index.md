---
title: Read()
second_title: Aspose.Slides for C++ APIリファレンス
description: ストリームから単一の文字を読み取ります。
type: docs
weight: 40
url: /ja/system.io/streamreader/read/
---
## StreamReader::Read() メソッド

ストリームから単一の文字を読み取ります。

```cpp
virtual int System::IO::StreamReader::Read() override
```

### 戻り値

UTF-16エンコーディングでエンコードされた文字を読み取ります。UTF-16エンコーディングで2つのコードポイントとして表される文字の場合、上位サロゲートのみが返されます。

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) メソッド

ストリームから指定された数の文字を読み取り、UTF-16エンコーディングに変換し、指定された位置から始まる指定された文字配列に結果のUTF-16文字を書き込みます。

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | ストリームから読み取った文字を書き込むためのUTF-16文字配列 |
| index | int | **buffer** の0ベースインデックスで、書き込みを開始する位置 |
| count | int | ストリームから読み取る文字数 |

### 戻り値

ストリームから読み取った文字数

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [StreamReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)