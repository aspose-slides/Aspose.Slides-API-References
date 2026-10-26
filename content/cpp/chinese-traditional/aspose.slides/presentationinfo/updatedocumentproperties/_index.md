---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API 參考
description: 更新已綁定簡報的屬性。
type: docs
weight: 92
url: /zh-hant/aspose.slides/presentationinfo/updatedocumentproperties/
---
## PresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) 方法

更新已綁定簡報的屬性。

```cpp
void Aspose::Slides::PresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties) override
```

## 備註

此範例展示如何呼叫 [PresentationInfo::UpdateDocumentProperties](./) 方法以更新由呼叫 [PresentationInfo::ReadDocumentProperties](../readdocumentproperties/) 方法返回的文件屬性。
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDocumentProperties](../../idocumentproperties/)
* 類別 [PresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)