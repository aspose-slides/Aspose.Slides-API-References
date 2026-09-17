---
title: IAudio class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iaudio/
---
## IAudio クラス

埋め込みオーディオファイルを表します。

IAudio 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`content_type`](/slides/python-net/ja/aspose.slides/iaudio/content_type/) | オーディオの MIME タイプを [`IAudio.binary_data`](/slides/python-net/ja/aspose.slides/iaudio/binary_data) でエンコードしたものを返します。<br/>            読み取り専用 **str**. |
| [`binary_data`](/slides/python-net/ja/aspose.slides/iaudio/binary_data/) | オーディオ データのコピーを返します。大量のデータの場合は、<br/>            [`IAudio.get_stream`](/slides/python-net/ja/aspose.slides/iaudio/get_stream) メソッドを使用して、オーディオの不要な読み込みを防止し、メモリに読み込むことや、OutOfMemoryException が発生することを防ぎます。<br/>            読み取り専用 **int**[]. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/ja/aspose.slides/iaudio/get_stream/#) | 読み取り用の Stream ストリームを返します。<br/>            'using' を使用するか、使用後にストリームを閉じてください。 |

### 関連項目
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)