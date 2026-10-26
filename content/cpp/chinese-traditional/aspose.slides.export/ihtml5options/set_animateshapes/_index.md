---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定形狀動畫選項。寫入 bool.
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) 方法


設定形狀動畫選項。寫入 **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## 備註


範例： 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## 另請參閱

* 類別 [IHtml5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)