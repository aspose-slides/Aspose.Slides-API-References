---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API リファレンス
description: "ソースフォントが見つからない場合に使用されるレギュラーフォントを設定します。System::String を書き込みます。"
type: docs
weight: 40
url: /ja/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) メソッド

ソースフォントが見つからない場合に使用されるレギュラーフォントを設定します。[System::String](../../../system/string/)を書きます。

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## 備考

次の例は、PowerPoint [Presentation](../../presentation/) のレンダリング用にデフォルトフォントを設定する方法を示しています。

```cpp
// ロードオプションを使用してデフォルトのレギュラーおよびアジアフォントを定義します
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// プレゼンテーションを読み込みます
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Generate slide thumbnail
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// PDF を生成します
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// XPS を生成します
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [LoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)