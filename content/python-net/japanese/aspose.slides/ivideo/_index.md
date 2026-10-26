---
title: IVideo class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ivideo/
---
## IVideo クラス

プレゼンテーションに埋め込まれたビデオを表します。

IVideo 型は次のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`content_type`](/slides/python-net/ja/aspose.slides/ivideo/content_type/) | ビデオの MIME タイプを [`IVideo.binary_data`](/slides/python-net/ja/aspose.slides/ivideo/binary_data) でエンコードしたものを返します。<br/>            読み取り専用 **str**. |
| [`binary_data`](/slides/python-net/ja/aspose.slides/ivideo/binary_data/) | オーディオ データのコピーを返します。大量のデータがある場合は、メモリにビデオ データを不要にロードしたり、OutOfMemoryException が発生したりしないように、<br/>            [`IVideo.get_stream`](/slides/python-net/ja/aspose.slides/ivideo/get_stream) メソッドの使用を検討してください。<br/>            読み取り専用 **int**[]. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ja/aspose.slides/ivideo/get_stream/#) | 読み取り用の Stream を返します。<br/>            使用後は 'using' を使用するか、ストリームを閉じてください。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)