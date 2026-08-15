---
title: GetRect()
second_title: Aspose.Slides for C++ API 參考
description: 取得界定部分的矩形座標。此矩形包含部分中所有文字行，包括空行。
type: docs
weight: 79
url: /zh-hant/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() 方法


取得界定部分的矩形座標。此矩形包含部分中所有文字行，包括空行。

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### 回傳值

界定部分的矩形 [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## 備註



範例： 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 50.0f, 50.0f, 200.0f, 50.0f);

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Clear();
auto portion0 = System::MakeObject<Portion>(u"Some text");
auto portion1 = System::MakeObject<Portion>(u"GetRect text");

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion0);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion1);

auto rect = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(1)->GetRect();
// ...
```

## 參見

* 類別 [RectangleF](../../../system.drawing/rectanglef/)
* 類別 [IPortion](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)