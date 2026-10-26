---
title: IStreamWrapper class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/istreamwrapper/
---
## IStreamWrapper クラス

COM インターフェイス用の Aspose.IO.Stream ラッパー。

IStreamWrapper 型は次のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`stream`](/slides/python-net/ja/aspose.slides/istreamwrapper/stream/) | ストリームを取得します。<br/>            読み取り専用 **io.RawIOBase**. |
| [`can_read`](/slides/python-net/ja/aspose.slides/istreamwrapper/can_read/) | 現在のストリームが読み取りをサポートしているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**. |
| [`can_seek`](/slides/python-net/ja/aspose.slides/istreamwrapper/can_seek/) | 現在のストリームがシークをサポートしているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**. |
| [`can_write`](/slides/python-net/ja/aspose.slides/istreamwrapper/can_write/) | 現在のストリームが書き込みをサポートしているかどうかを示す値を取得します。<br/>            読み取り専用 **bool**. |
| [`length`](/slides/python-net/ja/aspose.slides/istreamwrapper/length/) | ストリームの長さ（バイト単位）を取得します。<br/>            読み取り専用 **int**. |
| [`position`](/slides/python-net/ja/aspose.slides/istreamwrapper/position/) | 現在のストリーム内の位置を取得します。<br/>            読み取り専用 **int**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`close(self)`](/slides/python-net/ja/aspose.slides/istreamwrapper/close/#) | 現在のストリームを閉じ、すべてのリソースを解放します。 |
| [`flush(self)`](/slides/python-net/ja/aspose.slides/istreamwrapper/flush/#) | このストリームのすべてのバッファをクリアし、バッファリングされたデータを基になるデバイスに書き込みます。 |
| [`read(self, buffer, offset, count)`](/slides/python-net/ja/aspose.slides/istreamwrapper/read/#bytes-int-int) | 現在のストリームからバイトのシーケンスを読み取り、読み取ったバイト数だけストリーム内の位置を進めます。 |
| [`read_byte(self)`](/slides/python-net/ja/aspose.slides/istreamwrapper/read_byte/#) | ストリームから1バイトを読み取り、ストリーム内の位置を1バイト進めます。ストリームの末尾に達した場合は -1 を返します。 |
| [`seek(self, offset, origin)`](/slides/python-net/ja/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | 現在のストリーム内の位置を設定します |
| [`write(self, buffer, offset, count)`](/slides/python-net/ja/aspose.slides/istreamwrapper/write/#bytes-int-int) | バイトのシーケンスを書き込み、書き込んだバイト数だけこのストリーム内の現在位置を進めます。 |
| [`write_byte(self, value)`](/slides/python-net/ja/aspose.slides/istreamwrapper/write_byte/#int) | ストリームの現在位置に1バイトを書き込み、ストリーム内の位置を1バイト進めます。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)