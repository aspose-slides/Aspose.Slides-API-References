---
title: set_IsDecorative()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定「Mark as decorative」選項 讀/寫 bool.
type: docs
weight: 417
url: /zh-hant/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) 方法

設定「Mark as decorative」選項 讀/寫 **bool**.

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
```

## 備註


```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 另請參閱

* 類別 [IShape](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)