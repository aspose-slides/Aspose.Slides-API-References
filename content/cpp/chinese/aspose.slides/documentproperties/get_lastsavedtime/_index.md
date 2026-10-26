---
title: get_LastSavedTime()
second_title: Aspose.Slides C++ API 参考
description: "返回演示文稿最后一次修改的日期。值采用 UTC。对于 Presentation::get_DocumentProperties 为只读（因为在 IPresentation 对象保存过程中它会被内部更新）。可以通过方法 IPresentationInfo::ReadDocumentProperties 返回的 DocumentProperties 实例进行更改。请参阅 IPresentationInfo::UpdateDocumentProperties 方法概述中的示例。"
type: docs
weight: 378
url: /zh/aspose.slides/documentproperties/get_lastsavedtime/
---
## DocumentProperties::get_LastSavedTime() 方法

返回演示文稿上次修改的日期。值采用 UTC。在 [Presentation::get_DocumentProperties](../../presentation/get_documentproperties/) 情况下为只读（因为在 [IPresentation](../../ipresentation/) 对象保存过程中它会被内部更新）。可以通过方法 [IPresentationInfo::ReadDocumentProperties](../../ipresentationinfo/readdocumentproperties/) 返回的 [DocumentProperties](../) 实例进行更改。请参阅 [IPresentationInfo::UpdateDocumentProperties](../../ipresentationinfo/updatedocumentproperties/) 方法概述中的示例。

```cpp
System::DateTime Aspose::Slides::DocumentProperties::get_LastSavedTime() override
```

## 另见

* 类 [DateTime](../../../system/datetime/)
* 类 [DocumentProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)