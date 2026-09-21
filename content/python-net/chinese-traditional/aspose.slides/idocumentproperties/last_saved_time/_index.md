---
title: last_saved_time property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time 屬性
傳回簡報最後變更的日期。
值以 UTC 表示。
在 Presentation.DocumentProperties 情況下為唯讀（因為在 IPresentation 物件儲存過程中會在內部自動更新）。
可透過由方法 [`IPresentationInfo.read_document_properties`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/read_document_properties) 回傳的 DocumentProperties 實例進行變更
請參閱 **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** 方法摘要中的範例。

### 定義：
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```

### 另見
* 類別 [`IDocumentProperties`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)