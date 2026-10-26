---
title: set_LastSavedTime()
second_title: Aspose.Slides for C++ API 參考文件
description: "傳回簡報最後一次修改的日期。值以 UTC 表示。當使用 Presentation::get_DocumentProperties 時為唯讀（因為在 IPresentation 物件儲存過程中會內部更新）。可透過由 IPresentationInfo::ReadDocumentProperties 方法返回的 DocumentProperties 實例進行變更。請參閱 IPresentationInfo::UpdateDocumentProperties 方法摘要中的範例。"
type: docs
weight: 391
url: /zh-hant/aspose.slides/documentproperties/set_lastsavedtime/
---
## DocumentProperties::set_LastSavedTime(System::DateTime) 方法


返回簡報最後一次修改的日期。值以 UTC 表示。[Presentation::get_DocumentProperties](../../presentation/get_documentproperties/) 時為唯讀（因為在 [IPresentation](../../ipresentation/) 物件儲存過程中會內部更新）。可以透過 [DocumentProperties](../) 實例（由方法 [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) 返回）變更。請參閱 [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) 方法摘要中的範例。

```cpp
void Aspose::Slides::DocumentProperties::set_LastSavedTime(System::DateTime value) override
```

## 另請參閱

* 類別 [DateTime](../../../system/datetime/)
* 類別 [DocumentProperties](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)