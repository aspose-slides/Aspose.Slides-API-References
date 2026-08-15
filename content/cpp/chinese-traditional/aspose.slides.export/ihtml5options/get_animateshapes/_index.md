---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API 參考
description: 傳回形狀動畫選項。讀取 bool.
type: docs
weight: 27
url: /zh-hant/aspose.slides.export/ihtml5options/get_animateshapes/
---
## IHtml5Options::get_AnimateShapes() 方法


傳回形狀動畫選項。讀取 **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateShapes()=0
```

## 備註


範例: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## 另請參閱

* 類別 [IHtml5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)