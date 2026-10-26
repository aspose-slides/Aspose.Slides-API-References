---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考
description: 取得一個值，指示文字在渲染時是否不使用連字。當設定為 true 時，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 false。
type: docs
weight: 131
url: /zh-hant/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() method


取得一個值，指示文字是否在渲染時不使用連字。當設定為 **true**，連字將在渲染輸出中被停用。預設情況下，此屬性設定為 **false**。

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## 備註


範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // 在文字渲染中停用連字

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 參見

* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)