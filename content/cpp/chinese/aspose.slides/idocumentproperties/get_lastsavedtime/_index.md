---
title: get_LastSavedTime()
second_title: Aspose.Slides for C++ API 参考
description: "返回演示文稿上次修改的日期。值为 UTC。对于 Presentation.DocumentProperties 为只读（因为在 IPresentation 对象保存过程中会在内部更新）。可以通过 IPresentationInfo::ReadDocumentProperties 方法返回的 DocumentProperties 实例进行更改。请参阅 IPresentationInfo::UpdateDocumentProperties 方法摘要中的示例。"
type: docs
weight: 378
url: /zh/aspose.slides/idocumentproperties/get_lastsavedtime/
---
## IDocumentProperties::get_LastSavedTime() 方法

返回演示文稿上次修改的日期。值为 UTC 时间。只读，适用于 Presentation.DocumentProperties（因为在 [IPresentation](../../ipresentation/) 对象保存过程时会内部更新）。可通过由 [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) 方法返回的 [DocumentProperties](../../documentproperties/) 实例进行更改。请参阅 [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) 方法摘要中的示例。

```cpp
virtual System::DateTime Aspose::Slides::IDocumentProperties::get_LastSavedTime()=0
```

## 另请参见

* 类 [DateTime](../../../system/datetime/)
* 类 [IDocumentProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)