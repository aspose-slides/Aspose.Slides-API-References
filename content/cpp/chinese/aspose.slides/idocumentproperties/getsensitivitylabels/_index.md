---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API 参考
description: 从自定义文档属性（Microsoft Information Protection SDK Metadata）获取敏感度标签数组。
type: docs
weight: 872
url: /zh/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() 方法

获取自定义文档属性中的敏感度标签数组（Microsoft Information Protection SDK Metadata）。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## 备注

以下代码展示了如何将敏感度标签信息从自定义文档属性移动到现代 SensitivityLabels 集合：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 从自定义文档属性获取敏感度标签
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // 将标签添加到集合
    // 在这里可以添加对标签信息有效性的检查（标签是否可用等）
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 参见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISensitivityLabel](../../isensitivitylabel/)
* 类 [IDocumentProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)