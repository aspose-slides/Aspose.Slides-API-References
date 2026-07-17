---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API 参考
description: 从自定义文档属性（Microsoft Information Protection SDK 元数据）获取敏感度标签数组。
type: docs
weight: 859
url: /zh/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() 方法

获取来自自定义文档属性的敏感度标签数组（Microsoft Information Protection SDK Metadata）。

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## 备注

以下代码展示了如何将敏感度标签信息从自定义文档属性移动到现代 SensitivityLabels 集合中：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 从自定义文档属性获取敏感度标签
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // 将标签添加到集合中
    // 在此可以检查标签信息的有效性（标签是否可用等）
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 另见

* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [ISensitivityLabel](../../isensitivitylabel/)
* 类 [DocumentProperties](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)