---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考
description: 取得一個值，用於指示文字是否在未使用連字的情況下呈現。當設定為 true 時，連字將在輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/renderingoptions/get_disablefontligatures/
---
## RenderingOptions::get_DisableFontLigatures() 方法

取得一個值，用於指示文字是否在未使用連字的情況下呈現。當設定為 **true** 時，連字將在呈現的輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
bool Aspose::Slides::Export::RenderingOptions::get_DisableFontLigatures() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // 在文字渲染中停用連字

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## 另見

* 類別 [RenderingOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)