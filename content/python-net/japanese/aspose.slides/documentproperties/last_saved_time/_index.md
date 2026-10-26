---
title: last_saved_time property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/documentproperties/last_saved_time/
weight: 290
---
## last_saved_time プロパティ
プレゼンテーションが最後に変更された日時を返します。
            値は UTC です。
            Presentation.DocumentProperties の場合は読み取り専用です（IPresentation オブジェクトの保存プロセス中に内部で更新されるため）。
            [`IPresentationInfo.read_document_properties`](/slides/python-net/ja/aspose.slides/ipresentationinfo/read_document_properties) メソッドが返す DocumentProperties インスタンスを介して変更できます。
            例については **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** メソッド概要をご覧ください。

### 定義:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```

### 参照
* クラス [`DocumentProperties`](/slides/python-net/ja/aspose.slides/documentproperties)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)