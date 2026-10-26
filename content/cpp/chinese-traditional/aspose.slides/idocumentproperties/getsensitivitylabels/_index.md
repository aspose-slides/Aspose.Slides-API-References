---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API 參考手冊
description: 從自訂文件屬性（Microsoft Information Protection SDK 中的 Metadata）取得敏感性標籤陣列。
type: docs
weight: 872
url: /zh-hant/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() 方法

取得自訂文件屬性 (Microsoft Information Protection SDK Metadata) 中的敏感性標籤陣列。

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## 備註

以下程式碼示範如何將自訂文件屬性中的敏感性標籤資訊移轉至現代的 SensitivityLabels 集合：

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// 從自訂文件屬性取得敏感性標籤
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // 將標籤加入集合
    // 您可以在此加入對標籤資訊有效性的檢查（標籤是否可用等）
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## 另見

* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ISensitivityLabel](../../isensitivitylabel/)
* 類別 [IDocumentProperties](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)