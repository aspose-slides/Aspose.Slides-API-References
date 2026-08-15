---
title: get_IsDecorative()
second_title: Aspose.Slides C++ API 參考文件
description: 取得「標記為裝飾」選項，讀寫 bool.
type: docs
weight: 404
url: /zh-hant/aspose.slides/ishape/get_isdecorative/
---
## IShape::get_IsDecorative() 方法


取得「標記為裝飾」選項，讀寫 **bool**.

```cpp
virtual bool Aspose::Slides::IShape::get_IsDecorative()=0
```

## 備註



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## 另見

* 類別 [IShape](../)
* 命名空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)