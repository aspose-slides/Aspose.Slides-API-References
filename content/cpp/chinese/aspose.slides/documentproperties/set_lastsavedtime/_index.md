---
title: set_LastSavedTime()
second_title: Aspose.Slides for C++ API 参考
description: "返回演示文稿上次修改的日期。值为 UTC。对于 Presentation::get_DocumentProperties 为只读（因为在 IPresentation 对象保存过程中会在内部更新）。可以通过 IPresentationInfo::ReadDocumentProperties 方法返回的 DocumentProperties 实例进行更改。请参见 IPresentationInfo::UpdateDocumentProperties 方法摘要中的示例。"
type: docs
weight: 391
url: /zh/aspose.slides/documentproperties/set_lastsavedtime/
---
## DocumentProperties::set_LastSavedTime(System::DateTime) 方法

返回演示文稿上次修改的日期。值使用 UTC。在 [Presentation::get_DocumentProperties](../../presentation/get_documentproperties/) 情况下为只读（因为在 [IPresentation](../../ipresentation/) 对象保存过程期间会内部更新）。可以通过 [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) 方法返回的 [DocumentProperties](../) 实例进行更改。请参见 [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) 方法摘要中的示例。

```cpp
void Aspose::Slides::DocumentProperties::set_LastSavedTime(System::DateTime value) override
```

## 另请参见

* 类 [DateTime](../../../system/datetime/)
* 类 [DocumentProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)