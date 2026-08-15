---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定一個值，以指示文字在渲染時是否不使用連字。當設定為 true 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 53
url: /zh-hant/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) 方法


設定一個值，以指示文字是否在渲染時不使用連字。當設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## 備註


範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // 禁用文字渲染中的連字

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## 相關參考

* 類別 [IRenderingOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)