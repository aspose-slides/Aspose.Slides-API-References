---
title: set_LastSavedTime()
second_title: Aspose.Slides C++ API 参考
description: "返回演示文稿上次修改的日期。值为 UTC.P。如果是 Presentation.DocumentProperties，则为只读（因为在 IPresentation 对象保存过程中会内部更新）。可以通过返回的 DocumentProperties 实例并使用方法 IPresentationInfo::ReadDocumentProperties 进行更改。请参见 IPresentationInfo::UpdateDocumentProperties 方法摘要中的示例。"
type: docs
weight: 391
url: /zh/aspose.slides/idocumentproperties/set_lastsavedtime/
---
## IDocumentProperties::set_LastSavedTime(System::DateTime) 方法

返回演示文稿上次修改的日期。值采用 UTC.P。如果是 Presentation.DocumentProperties，则为只读（因为在 [IPresentation](../../ipresentation/) 对象保存过程中会内部更新）。可以通过 [DocumentProperties](../../documentproperties/) 实例并使用 [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) 方法进行更改。请参见 [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) 方法摘要中的示例。

```cpp
virtual void Aspose::Slides::IDocumentProperties::set_LastSavedTime(System::DateTime value)=0
```

## 另请参阅

* 类 [DateTime](../../../system/datetime/)
* 类 [IDocumentProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)