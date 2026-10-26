---
title: only_load_document_properties property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties プロパティ
このプロパティは、プレゼンテーションファイルがパスワードで保護されている場合に意味があります。
            true の値は、暗号化されたプレゼンテーションファイルからドキュメントプロパティのみをロードし、パスワードは無視することを意味します。
            false の値は、正しいパスワードを使用して暗号化されたプレゼンテーション全体をロードすることを意味します。
            プレゼンテーションが暗号化されていない場合、プロパティの値は常に無視されます。
            暗号化されたファイルのドキュメントプロパティが公開されておらず、プロパティの値が true の場合、ドキュメントプロパティはロードできず、例外がスローされます。
            読み取り/書き込み **bool**。

### Definition:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### See Also
* class [`LoadOptions`](/slides/python-net/ja/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)