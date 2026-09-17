---
title: VbaProject class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.vba/vbaproject/
---
## VbaProject クラス

プレゼンテーション マクロを含む VBA プロジェクトを表します。

VbaProject 型は次のメンバーを公開します。

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ja/aspose.slides.vba/vbaproject/__init__/#) | このコンストラクタは新しい VBA プロジェクトを最初から作成します。<br/>            プロジェクトは 1252 Windows Latin 1 (ANSI) コードページで作成されます |
| [`__init__(self, data)`](/slides/python-net/ja/aspose.slides.vba/vbaproject/__init__/#bytes) | このコンストラクタは OLE コンテナのバイナリ表現から VBA プロジェクトを読み込みます。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`name`](/slides/python-net/ja/aspose.slides.vba/vbaproject/name/) | VBA プロジェクトの名前を返します。読み取り専用 **str**。 |
| [`modules`](/slides/python-net/ja/aspose.slides.vba/vbaproject/modules/) | VBA プロジェクトに含まれるすべてのモジュールの一覧を返します。読み取り専用 [`IVbaModuleCollection`](/slides/python-net/ja/aspose.slides.vba/ivbamodulecollection)。 |
| [`references`](/slides/python-net/ja/aspose.slides.vba/vbaproject/references/) | VBA プロジェクトに含まれるすべての参照の一覧を返します。読み取り専用 [`IVbaReferenceCollection`](/slides/python-net/ja/aspose.slides.vba/ivbareferencecollection)。 |
| [`is_password_protected`](/slides/python-net/ja/aspose.slides.vba/vbaproject/is_password_protected/) | VBAProject がパスワードで保護され、プロジェクト プロパティの表示が制限されているかどうかを示します。読み取り専用 **bool**。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`to_binary(self)`](/slides/python-net/ja/aspose.slides.vba/vbaproject/to_binary/#) | VBA プロジェクトのバイナリ表現を OLE コンテナとして返します |

### 参照
* モジュール [`aspose.slides.vba`](/slides/python-net/ja/aspose.slides.vba)
* ライブラリ [`Aspose.Slides`](/slides/python-net)