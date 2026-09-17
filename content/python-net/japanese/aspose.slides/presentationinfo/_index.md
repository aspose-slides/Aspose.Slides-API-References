---
title: PresentationInfo class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentationinfo/
---
## PresentationInfo クラス

プレゼンテーション ファイルに関する情報

PresentationInfo 型は以下のメンバーを公開します:

## プロパティ

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/ja/aspose.slides/presentationinfo/is_encrypted/) | バインドされたプレゼンテーションが暗号化されている場合は True を取得し、そうでない場合は False を取得します。<br/>            読み取り専用 **bool**. |
| [`is_password_protected`](/slides/python-net/ja/aspose.slides/presentationinfo/is_password_protected/) | バインドされたプレゼンテーションが開くためのパスワードで保護されているかどうかを示す値を取得します。 |
| [`is_write_protected`](/slides/python-net/ja/aspose.slides/presentationinfo/is_write_protected/) | バインドされたプレゼンテーションが書き込み保護されているかどうかを示す値を取得します。 |
| [`load_format`](/slides/python-net/ja/aspose.slides/presentationinfo/load_format/) | バインドされたプレゼンテーションの形式を取得します。<br/>            読み取り専用 [`LoadFormat`](/slides/python-net/ja/aspose.slides/loadformat). |

## メソッド

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/ja/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | バインドされたプレゼンテーションを書き込んでストリームに出力します。 |
| [`write_binded_presentation(self, file)`](/slides/python-net/ja/aspose.slides/presentationinfo/write_binded_presentation/#str) | バインドされたプレゼンテーションを書き込んでファイルに保存します。 |
| [`check_password(self, password)`](/slides/python-net/ja/aspose.slides/presentationinfo/check_password/#str) | 開くパスワードで保護されたプレゼンテーションに対し、パスワードが正しいかどうかをチェックします。 |
| [`check_write_protection(self, password)`](/slides/python-net/ja/aspose.slides/presentationinfo/check_write_protection/#str) | 書き込み保護されたプレゼンテーションに対し、変更用パスワードが正しいかどうかをチェックします。 |
| [`read_document_properties(self)`](/slides/python-net/ja/aspose.slides/presentationinfo/read_document_properties/#) | バインドされたプレゼンテーションのドキュメント プロパティを取得します。 |
| [`update_document_properties(self, document_properties)`](/slides/python-net/ja/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | バインドされたプレゼンテーションのプロパティを更新します。 |

### 関連項目
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)