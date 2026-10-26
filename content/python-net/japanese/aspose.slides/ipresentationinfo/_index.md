---
title: IPresentationInfo class
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentationinfo/
---
## IPresentationInfo クラス

プレゼンテーション ファイルに関する情報

IPresentationInfo 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/ja/aspose.slides/ipresentationinfo/is_encrypted/) | バインドされたプレゼンテーションが暗号化されている場合は True を取得し、そうでない場合は False を取得します。<br/>            読み取り専用 **bool**. |
| [`is_password_protected`](/slides/python-net/ja/aspose.slides/ipresentationinfo/is_password_protected/) | バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。 |
| [`is_write_protected`](/slides/python-net/ja/aspose.slides/ipresentationinfo/is_write_protected/) | バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。 |
| [`load_format`](/slides/python-net/ja/aspose.slides/ipresentationinfo/load_format/) | バインドされたプレゼンテーションの形式を取得します。<br/>            読み取り専用 [`LoadFormat`](/slides/python-net/ja/aspose.slides/loadformat). |

## メソッド

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/ja/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | バインドされたプレゼンテーションをストリームに書き込みます。 |
| [`write_binded_presentation(self, file)`](/slides/python-net/ja/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | バインドされたプレゼンテーションをファイルに書き込みます。 |
| [`check_password(self, password)`](/slides/python-net/ja/aspose.slides/ipresentationinfo/check_password/#str) | 開くためのパスワードで保護されたプレゼンテーションのパスワードが正しいかどうかを確認します。 |
| [`check_write_protection(self, password)`](/slides/python-net/ja/aspose.slides/ipresentationinfo/check_write_protection/#str) | 書き込み保護されたプレゼンテーションの変更用パスワードが正しいかどうかを確認します。 |
| [`read_document_properties(self)`](/slides/python-net/ja/aspose.slides/ipresentationinfo/read_document_properties/#) | バインドされたプレゼンテーションのドキュメント プロパティを取得します。 |
| [`update_document_properties(self, document_properties)`](/slides/python-net/ja/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | バインドされたプレゼンテーションのプロパティを更新します。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)