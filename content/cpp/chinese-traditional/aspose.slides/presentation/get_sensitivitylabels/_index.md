---
title: get_SensitivityLabels()
second_title: Aspose.Slides for C++ API 參考
description: 返回套用于簡報文件的敏感性標籤集合。唯讀 ISensitivityLabelCollection.
type: docs
weight: 378
url: /zh-hant/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() 方法


返回套用于簡報文件的敏感性標籤集合。唯讀 [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// 列印已套用的標籤
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// 新增標籤
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// 從原則取得敏感性標籤 Id
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// 從原則取得 Azure AD 站點識別碼
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* 類別 [Presentation](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)