---
title: set_AnimateTransitions()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定過渡動畫選項。寫入 bool.
type: docs
weight: 14
url: /zh-hant/aspose.slides.export/ihtml5options/set_animatetransitions/
---
## IHtml5Options::set_AnimateTransitions(bool) 方法


設定過渡動畫選項。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateTransitions(bool value)=0
```

## 備註


範例：
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## 另見

* 類別 [IHtml5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)