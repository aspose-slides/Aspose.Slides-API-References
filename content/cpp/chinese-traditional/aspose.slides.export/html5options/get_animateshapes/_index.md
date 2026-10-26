---
title: get_AnimateShapes()
second_title: Aspose.Slides for C++ API 參考
description: 返回形狀動畫選項。讀取 bool。
type: docs
weight: 27
url: /zh-hant/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() method

返回形狀動畫選項。讀取 **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
```

## 備註

範例： 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## 另見

* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)