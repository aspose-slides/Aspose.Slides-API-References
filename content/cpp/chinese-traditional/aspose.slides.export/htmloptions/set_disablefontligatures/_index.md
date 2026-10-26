---
title: set_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定一個值，以指示文字在渲染時是否不使用連字。當設定為 true 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 105
url: /zh-hant/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) 方法


設定一個值，以指示文字在渲染時是否不使用連字。當設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // 在文字渲染時停用連字

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 另請參閱

* 類別 [HtmlOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)