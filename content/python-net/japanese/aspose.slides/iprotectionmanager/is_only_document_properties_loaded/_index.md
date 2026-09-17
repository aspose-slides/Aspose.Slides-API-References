---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded プロパティ
This property makes sense, if presentation file is password protected and document 
            properties of this file are public.
            Value of true means that only document properties are loaded from an encrypted 
            presentation file without use of password.
            Value of false means that entire encrypted presentation is loaded with use of right 
            password, not only document properties are loaded.
            If presentation isn’t encrypted then property value is always false.
            If document properties of an encrypted file aren’t public then property value is always false.
            If PresentationEx.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded 
            property value is always false.
            Read-only **bool**.

### 定義:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### 参照
* クラス [`IProtectionManager`](/slides/python-net/ja/aspose.slides/iprotectionmanager)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)