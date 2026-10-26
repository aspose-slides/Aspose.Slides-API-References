---
title: DigitalSignature class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/digitalsignature/
---
## DigitalSignature クラス

署名済みファイルのデジタル署名。

DigitalSignature 型は以下のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, certificate)`](/slides/python-net/ja/aspose.slides/digitalsignature/__init__/#systemsecuritycryptographyx509certificatesx509certificate2) | 指定された証明書で新しい DigitalSignature オブジェクトを作成します。 |
| [`__init__(self, file_path, password)`](/slides/python-net/ja/aspose.slides/digitalsignature/__init__/#str-str) | 指定された証明書ファイルパスとパスワードで新しい DigitalSignature オブジェクトを作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`certificate`](/slides/python-net/ja/aspose.slides/digitalsignature/certificate/) | ドキュメントの署名に使用された証明書オブジェクト。<br/>            読み取り専用 **System.Security.Cryptography.X509Certificates.X509Certificate2**. |
| [`is_valid`](/slides/python-net/ja/aspose.slides/digitalsignature/is_valid/) | このデジタル署名が有効で、ドキュメントが改ざんされていない場合、この値は true になります。<br/>            読み取り専用 **bool**. |
| [`sign_time`](/slides/python-net/ja/aspose.slides/digitalsignature/sign_time/) | ドキュメントが署名された日時。<br/>            読み取り専用 **System.DateTime**. |
| [`comments`](/slides/python-net/ja/aspose.slides/digitalsignature/comments/) | 署名の目的。<br/>            読み書き可能 **str**. |


### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)