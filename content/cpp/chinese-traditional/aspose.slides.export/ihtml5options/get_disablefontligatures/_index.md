---
title: get_DisableFontLigatures()
second_title: Aspose.Slides for C++ API 參考
description: 取得一個值，指示文字在渲染時是否不使用連字。設定為 true 時，渲染輸出將停用連字。預設情況下，此屬性為 false。
type: docs
weight: 131
url: /zh-hant/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() 方法

取得一個值，指示文字是否在渲染時不使用連字。當設定為 **true** 時，渲染輸出中將停用連字。預設情況下，此屬性為 **false**。

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## 備註

範例：
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // 在文字渲染時停用連字

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## 參見

* 類別 [IHtml5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)