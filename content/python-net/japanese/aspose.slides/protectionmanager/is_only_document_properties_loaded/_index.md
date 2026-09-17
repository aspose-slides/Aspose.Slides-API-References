---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded プロパティ
このプロパティは、プレゼンテーション ファイルがパスワードで保護され、かつこのファイルのドキュメント プロパティが公開されている場合に意味があります。
true の場合は、パスワードを使用せずに暗号化されたプレゼンテーション ファイルからドキュメント プロパティのみが読み込まれることを意味します。
false の場合は、正しいパスワードを使用して暗号化されたプレゼンテーション全体が読み込まれ、ドキュメント プロパティだけでなく全体が読み込まれます。
プレゼンテーションが暗号化されていない場合、プロパティ値は常に false です。
暗号化されたファイルのドキュメント プロパティが公開されていない場合、プロパティ値は常に false です。
Presentation.EncryptDocumentProperties が true の場合、IsOnlyDocumentPropertiesLoaded プロパティの値は常に false です。
読み取り専用 **bool**。

### 定義:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### 参照
* クラス [`ProtectionManager`](/slides/python-net/ja/aspose.slides/protectionmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)