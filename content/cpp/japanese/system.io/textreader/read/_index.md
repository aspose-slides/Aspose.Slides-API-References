---
title: Read()
second_title: C++ 用 Aspose.Slides API リファレンス
description: ストリームから単一文字を読み取ります。
type: docs
weight: 40
url: /ja/system.io/textreader/read/
---
## TextReader::Read() メソッド

ストリームから単一文字を読み取ります。

```cpp
virtual int System::IO::TextReader::Read()
```

### 戻り値

UTF-16 エンコーディングでエンコードされた文字を読み取ります。読み取った文字が UTF-16 エンコーディングで 2 つのコードポイントで表される場合、上位サロゲートのみが返されます。

## TextReader::Read(ArrayPtr\<char_t\>, int, int) メソッド

ストリームから指定された文字数を読み取り、指定された位置から開始して指定された文字配列に書き込みます。

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | ストリームから読み取った文字を書き込むための UTF-16 文字配列 |
| index | int | **buffer** の 0 基準インデックスで、書き込みを開始する位置 |
| count | int | ストリームから読み取る文字数 |

### 戻り値

ストリームから読み取った文字数

## 関連項目

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [TextReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)