---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API 參考
description: 從自訂文件屬性 (Microsoft Information Protection SDK Metadata) 取得敏感度標籤的陣列。
type: docs
weight: 859
url: /zh-hant/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() 方法


從自訂文件屬性 (Microsoft Information Protection SDK Metadata) 取得敏感度標籤的陣列。

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## 備註


以下程式碼示範如何將自訂文件屬性中的敏感度標籤資訊移轉到現代的 SensitivityLabels 集合：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 從自訂文件屬性取得敏感度標籤
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // 將標籤新增至集合
    // 在此您可以加入檢查標籤資訊有效性的程式（標籤是否可用等）
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 另見

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [ISensitivityLabel](../../isensitivitylabel/)
* 類別 [DocumentProperties](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)