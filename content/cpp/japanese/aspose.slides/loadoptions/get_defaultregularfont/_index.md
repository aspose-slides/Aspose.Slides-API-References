---
title: get_DefaultRegularFont()
second_title: Aspose.Slides for C++ API リファレンス
description: "ソースフォントが見つからない場合に使用される Regular フォントを返します。System::String を参照してください。"
type: docs
weight: 27
url: /ja/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() メソッド


ソースフォントが見つからない場合に使用される Regular フォントを返します。参照 [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## 備考


以下の例は、PowerPoint [Presentation](../../presentation/) のレンダリング時にデフォルトフォントを設定する方法を示します。
```cpp
// ロードオプションを使用してデフォルトのレギュラーフォントとアジアンフォントを定義します
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// プレゼンテーションをロードします
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generate slide thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Generate PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Generate XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [LoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)