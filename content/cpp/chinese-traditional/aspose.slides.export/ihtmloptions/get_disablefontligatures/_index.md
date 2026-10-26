---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得一個值，指示文字在渲染時是否不使用連字。設定為 true 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 183
url: /zh-hant/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() 方法


取得一個值，指示文字是否在渲染時不使用連字。設定為 **true** 時，連字將會在渲染輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## 備註


範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // 在文字渲染中停用連字

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## 另請參見

* 類別 [IHtmlOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)