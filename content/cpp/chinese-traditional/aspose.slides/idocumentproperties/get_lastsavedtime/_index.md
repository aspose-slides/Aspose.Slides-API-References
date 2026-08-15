---
title: get_LastSavedTime()
second_title: Aspose.Slides C++ API 參考
description: "傳回簡報最後一次修改的日期。值以 UTC 為單位。Presentation.DocumentProperties 為唯讀（因為在 IPresentation 物件儲存過程中會內部更新）。可透過 IPresentationInfo::ReadDocumentProperties 方法返回的 DocumentProperties 實例進行變更。請參考 IPresentationInfo::UpdateDocumentProperties 方法摘要中的範例。"
type: docs
weight: 378
url: /zh-hant/aspose.slides/idocumentproperties/get_lastsavedtime/
---
## IDocumentProperties::get_LastSavedTime() 方法


傳回簡報最後一次修改的日期。值以 UTC 為單位。唯讀於 Presentation.DocumentProperties（因為在 [IPresentation](../../ipresentation/) 物件儲存過程中會內部更新）。可透過 [DocumentProperties](../../documentproperties/) 實例（由方法 [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) 返回）更改。請參考 [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) 方法摘要中的範例。

```cpp
virtual System::DateTime Aspose::Slides::IDocumentProperties::get_LastSavedTime()=0
```

## 參見

* 類別 [DateTime](../../../system/datetime/)
* 類別 [IDocumentProperties](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)