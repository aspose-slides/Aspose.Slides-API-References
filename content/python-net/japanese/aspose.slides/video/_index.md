---
title: Video class
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/video/
---
## Video クラス

プレゼンテーションに埋め込まれた画像を表します。

Video 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`content_type`](/slides/python-net/ja/aspose.slides/video/content_type/) | Returns a MIME type of an video, encoded in [`Video.binary_data`](/slides/python-net/ja/aspose.slides/video/binary_data).<br/>            読み取り専用 **str**。 |
| [`binary_data`](/slides/python-net/ja/aspose.slides/video/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider using of <br/>            [`Video.get_stream`](/slides/python-net/ja/aspose.slides/video/get_stream) method to prevent unnecessary loading of video's data into memory <br/>            or even OutOfMemoryException.<br/>            読み取り専用 **int**[]。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ja/aspose.slides/video/get_stream/#) | Returns Stream stream for reading.<br/>            使用後は 'using' を使用するか、ストリームを閉じてください。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)