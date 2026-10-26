---
title: get_IsDecorative()
second_title: Aspose.Slides C++ API 參考
description: 取得「Mark as decorative」選項，讀/寫 bool.
type: docs
weight: 521
url: /zh-hant/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() 方法


取得 'Mark as decorative' 選項 讀/寫 **bool**。

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 另見

* 類別 [Shape](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)