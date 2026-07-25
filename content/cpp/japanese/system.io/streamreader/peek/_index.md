---
title: Peek()
second_title: Aspose.Slides for C++ API リファレンス
description: ストリームの読み取りカーソルを変更せずに、ストリームから単一の文字を読み取ります。
type: docs
weight: 27
url: /ja/system.io/streamreader/peek/
---
## StreamReader::Peek() メソッド


ストリームから単一の文字を読み取りますが、ストリームの読み取りカーソルは変更しません。

```cpp
virtual int System::IO::StreamReader::Peek() override
```


### 戻り値

UTF-16 エンコーディングでエンコードされた文字を返します。読み取った文字が UTF-16 で 2 つのコードポイントで表される場合、高位サロゲートのみが返されます。文字が読み取れなかった場合は -1 が返されます

## 参照

* クラス [StreamReader](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)