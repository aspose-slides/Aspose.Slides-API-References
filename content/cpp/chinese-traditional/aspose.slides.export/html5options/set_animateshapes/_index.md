---
title: set_AnimateShapes()
second_title: Aspose.Slides for C++ API 參考
description: 設定形狀動畫選項。寫入 bool.
type: docs
weight: 40
url: /zh-hant/aspose.slides.export/html5options/set_animateshapes/
---
## Html5Options::set_AnimateShapes(bool) 方法


設定形狀動畫選項。寫入 **bool**.

```cpp
void Aspose::Slides::Export::Html5Options::set_AnimateShapes(bool value) override
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

* 類別 [Html5Options](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)