---
title: Peek()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームの読み取りカーソルを変更せずに、ストリームから単一の文字を読み取ります。
type: docs
weight: 27
url: /ja/system.io/textreader/peek/
---
## TextReader::Peek() メソッド


ストリームの読み取りカーソルを変更せずに、ストリームから単一の文字を読み取ります。

```cpp
virtual int System::IO::TextReader::Peek()
```


### 戻り値

UTF-16 エンコーディングでエンコードされた文字を読み取ります；読み取った文字が UTF-16 で二つのコードポイントで表される場合は、高サロゲートのみが返されます；文字が読み取れなかった場合は -1 が返されます

## 参照

* クラス [TextReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)