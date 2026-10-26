---
title: StreamWrapper class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/streamwrapper/
---
## StreamWrapper クラス

COM インターフェイス用の Aspose.IO.Stream ラッパー。

StreamWrapper 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`stream`](/slides/python-net/ja/aspose.slides/streamwrapper/stream/) | ストリームを取得します。<br/>            読み取り専用 **io.RawIOBase**。 |
| [`can_read`](/slides/python-net/ja/aspose.slides/streamwrapper/can_read/) | 現在のストリームが読み取りをサポートしているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**。 |
| [`can_seek`](/slides/python-net/ja/aspose.slides/streamwrapper/can_seek/) | 現在のストリームがシークをサポートしているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**。 |
| [`can_write`](/slides/python-net/ja/aspose.slides/streamwrapper/can_write/) | 現在のストリームが書き込みをサポートしているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**。 |
| [`length`](/slides/python-net/ja/aspose.slides/streamwrapper/length/) | ストリームのバイト単位の長さを取得します。<br/>            読み取り専用 **int**。 |
| [`position`](/slides/python-net/ja/aspose.slides/streamwrapper/position/) | 現在のストリーム内の位置を取得または設定します。<br/>            読み取り専用 **int**。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`close(self)`](/slides/python-net/ja/aspose.slides/streamwrapper/close/#) | 現在のストリームを閉じ、すべてのリソースを解放します。 |
| [`flush(self)`](/slides/python-net/ja/aspose.slides/streamwrapper/flush/#) | このストリームのすべてのバッファをクリアし、バッファされたデータを書き込み先デバイスに書き込みます。 |
| [`read(self, buffer, offset, count)`](/slides/python-net/ja/aspose.slides/streamwrapper/read/#bytes-int-int) | 現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| [`read_byte(self)`](/slides/python-net/ja/aspose.slides/streamwrapper/read_byte/#) | ストリームから1バイトを読み取り、ストリーム内の位置を1バイト進めます。ストリームの末尾にある場合は -1 を返します。 |
| [`seek(self, offset, origin)`](/slides/python-net/ja/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | 現在のストリーム内の位置を設定します |
| [`write(self, buffer, offset, count)`](/slides/python-net/ja/aspose.slides/streamwrapper/write/#bytes-int-int) | 現在のストリームにバイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在の位置を進めます。 |
| [`write_byte(self, value)`](/slides/python-net/ja/aspose.slides/streamwrapper/write_byte/#int) | ストリームの現在位置に1バイトを書き込み、ストリーム内の位置を1バイト進めます。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)