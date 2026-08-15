---
title: set_IsDecorative()
second_title: Aspose.Slides for C++ API 參考
description: 設定「Mark as decorative」選項 讀/寫 bool.
type: docs
weight: 534
url: /zh-hant/aspose.slides/shape/set_isdecorative/
---
## Shape::set_IsDecorative(bool) 方法


設定「Mark as decorative」選項 讀/寫 **bool**.

```cpp
void Aspose::Slides::Shape::set_IsDecorative(bool value) override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 相關參考

* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)