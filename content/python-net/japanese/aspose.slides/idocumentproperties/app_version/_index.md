---
title: app_version property
second_title: Aspose.Slides for Python via .NET の API リファレンス
description: 
type: docs
url: /ja/aspose.slides/idocumentproperties/app_version/
weight: 90
---
## app_version プロパティ
アプリのバージョンを返します。
            読み取り専用 **str**.

### 備考

The content of this element shall be in the form XX.YYYY, where X and Y represent numerical values;
            otherwise, the document shall be considered non-conformant.
            Aspose.Slides represents its version in the format XX.YYZZ, where:
            XX - メジャーバージョン
            YY - マイナーバージョン
            ZZ - パッチバージョン
            For example, the value 23.0105 means Aspose.Slides version 23.1.5.

### 定義:
```python
@property
def app_version(self):
    ...
```

### 参照
* クラス [`IDocumentProperties`](/slides/python-net/ja/aspose.slides/idocumentproperties)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)