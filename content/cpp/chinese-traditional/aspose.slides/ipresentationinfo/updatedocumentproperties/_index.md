---
title: UpdateDocumentProperties()
second_title: Aspose.Slides for C++ API 參考
description: 更新已綁定簡報的屬性。
type: docs
weight: 92
url: /zh-hant/aspose.slides/ipresentationinfo/updatedocumentproperties/
---
## IPresentationInfo::UpdateDocumentProperties(System::SharedPtr\<IDocumentProperties\>) method

更新已綁定簡報的屬性。

```cpp
virtual void Aspose::Slides::IPresentationInfo::UpdateDocumentProperties(System::SharedPtr<IDocumentProperties> documentProperties)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| documentProperties | [System::SharedPtr](../../../system/sharedptr/)\<[IDocumentProperties](../../idocumentproperties/)\> | 文件屬性 [IDocumentProperties](../../idocumentproperties/) |
## 備註

此範例示範如何呼叫 [IPresentationInfo::UpdateDocumentProperties](./) 方法以更新由呼叫 [IPresentationInfo::ReadDocumentProperties](../readdocumentproperties/) 方法所回傳的文件屬性。
```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
auto props = info->ReadDocumentProperties();
props->set_Subject(u"New subject");
props->set_LastSavedTime(System::DateTime::get_UtcNow());
info->UpdateDocumentProperties(props);
info->WriteBindedPresentation(u"new_pres.pptx");
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDocumentProperties](../../idocumentproperties/)
* 類別 [IPresentationInfo](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)