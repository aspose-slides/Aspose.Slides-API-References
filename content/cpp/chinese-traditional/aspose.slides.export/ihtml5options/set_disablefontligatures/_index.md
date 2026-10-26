---
title: set_DisableFontLigatures()
second_title: Aspose.Slides C++ API 參考
description: 設定一個值以指示文字是否在渲染時不使用連字。當設定為 true 時，連字將在渲染輸出中被停用。預設情況下，該屬性設定為 false。
type: docs
weight: 144
url: /zh-hant/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) 方法


設定一個值以指示文字是否在渲染時不使用連字。當設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，該屬性設定為 **false**。

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // 在文字渲染中停用連字

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 另請參閱

* 類別 [IHtml5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)