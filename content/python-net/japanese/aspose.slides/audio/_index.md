---
title: Audio class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/audio/
---
## Audio クラス

埋め込みオーディオファイルを表します。

Audio 型は次のメンバーを公開します：

## プロパティ

| Property | 説明 |
| :- | :- |
| [`content_type`](/slides/python-net/ja/aspose.slides/audio/content_type/) | オーディオの MIME タイプを [`Audio.binary_data`](/slides/python-net/ja/aspose.slides/audio/binary_data) でエンコードして返します。<br/>            読み取り専用 **str**。 |
| [`binary_data`](/slides/python-net/ja/aspose.slides/audio/binary_data/) | オーディオデータのコピーを返します。データ量が大きい場合は、<br/>            [`Audio.get_stream`](/slides/python-net/ja/aspose.slides/audio/get_stream) メソッドの使用を検討して、オーディオのデータをメモリに不要にロードしたり、OutOfMemoryException が発生したりするのを防止してください。<br/>            読み取り専用 **int**[]。 |

## メソッド

| Method | 説明 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ja/aspose.slides/audio/get_stream/#) | 読み取り用の Stream ストリームを返します。<br/>            'using' を使用するか、使用後にストリームを閉じてください。 |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)