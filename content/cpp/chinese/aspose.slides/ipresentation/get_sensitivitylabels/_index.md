---
title: get_SensitivityLabels()
second_title: Aspose.Slides for C++ API 参考
description: 返回应用于演示文稿文档的敏感度标签集合。只读 ISensitivityLabelCollection.
type: docs
weight: 391
url: /zh/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() 方法

返回应用于演示文稿文档的敏感度标签集合。只读 [ISensitivityLabelCollection](../../isensitivitylabelcollection/)。

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## 备注

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// 打印已应用的标签
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// 添加新标签
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// 从策略获取敏感度标签 ID
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// 从策略获取 Azure AD 站点标识符
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* 类 [IPresentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)