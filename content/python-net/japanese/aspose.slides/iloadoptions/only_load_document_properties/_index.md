---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties プロパティ
このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。
true の値は、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみを読み込み、パスワードを無視しなければならないことを意味します。
false の値は、正しいパスワードを使用して暗号化されたプレゼンテーション全体を読み込む必要があることを意味します。
プレゼンテーションが暗号化されていない場合、プロパティの値は常に無視されます。
暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティの値が true の場合、ドキュメントプロパティを読み込むことができず、例外がスローされます。
読み書き可能 **bool**。

### 定義:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### 参照
* クラス [`ILoadOptions`](/slides/python-net/ja/aspose.slides/iloadoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)