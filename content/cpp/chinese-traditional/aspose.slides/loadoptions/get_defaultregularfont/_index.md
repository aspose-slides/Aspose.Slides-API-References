---
title: get_DefaultRegularFont()
second_title: Aspose.Slides for C++ API 參考文件
description: "如果找不到來源字型，則返回使用的常規字型。請閱讀 System::String."
type: docs
weight: 27
url: /zh-hant/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() 方法

返回在未找到來源字型時使用的常規字型。請參閱 [System::String](../../../system/string/)。

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## 備註

以下範例說明如何設定渲染 PowerPoint [Presentation](../../presentation/) 的預設字型。

```cpp
// 使用載入選項定義預設的常規和亞洲字型
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

## 另請參閱

* 類別 [String](../../../system/string/)
* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)