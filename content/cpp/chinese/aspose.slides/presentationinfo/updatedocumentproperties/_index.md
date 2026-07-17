---
title: UpdateDocumentProperties()
second_title: Aspose.Slides C++ API 参考
description: 更新已绑定演示文稿的属性。
type: docs
weight: 92
url: /zh/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) 方法


Updates properties of binded presentation.

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## 备注


此示例展示了如何调用 [PresentationInfo::UpdateDocumentProperties](./) 方法来更新通过调用 [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) 方法返回的文档属性。

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDocumentProperties](../../idocumentproperties/)
* 类 [PresentationInfo](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)