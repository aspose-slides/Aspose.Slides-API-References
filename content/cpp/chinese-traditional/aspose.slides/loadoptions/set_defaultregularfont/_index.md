---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API 參考
description: "設定在找不到原始字型時使用的常規字型。寫入 System::String."
type: docs
weight: 40
url: /zh-hant/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) 方法


設定在找不到原始字型時使用的常規字型。寫入 [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## 備註


以下範例說明如何設定 PowerPoint [Presentation](../../presentation/) 的預設字型以進行轉譯。 
```cpp
// 使用載入選項來定義預設的常規字型和亞洲字型
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// 載入簡報
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// 產生投影片縮圖
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// 產生 PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// 產生 XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## 另見

* 類別 [String](../../../system/string/)
* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)