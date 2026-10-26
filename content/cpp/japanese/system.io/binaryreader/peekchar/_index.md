---
title: PeekChar()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームの読み取りカーソルを変更せずに、入力ストリームから単一の文字を読み取ります。
type: docs
weight: 53
url: /ja/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() メソッド

入力ストリームから単一の文字を読み取り、ストリームの読み取りカーソルは変更しません。

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### 戻り値

UTF-16 エンコーディングでエンコードされた文字を返します。読み取った文字が UTF-16 エンコーディングで 2 つのコードポイントで表される場合は、上位サロゲートのみが返されます。文字が読み取れなかった場合は -1 が返されます。

## 参照

* クラス [BinaryReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)