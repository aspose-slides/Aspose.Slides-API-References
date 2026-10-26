---
title: set_AnimateTransitions()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定過渡動畫選項。寫入 bool。
type: docs
weight: 14
url: /zh-hant/aspose.slides.export/html5options/set_animatetransitions/
---
## Html5Options::set_AnimateTransitions(bool) 方法


設定過渡動畫選項。寫入 **bool**。

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateTransitions(bool value) override
```

## 備註


範例:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## 參見

* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)