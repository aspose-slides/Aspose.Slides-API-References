---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考
description: 取得一個值，用於指示文字是否在渲染時不使用連字。設定為 true 時，連字將在渲染輸出中被停用。預設情況下，此屬性設為 false.
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() 方法

取得一個值，用於指示文字是否在渲染時不使用連字。設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，此屬性設為 **false**。

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // 在文字渲染中停用連字

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 另請參閱

* 類別 [HtmlOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)