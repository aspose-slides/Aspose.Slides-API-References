---
title: GetRect()
second_title: Aspose.Slides C++ API 參考
description: 取得包圍區段的矩形座標。該矩形包含區段中的所有文字行，亦包括空行。
type: docs
weight: 92
url: /zh-hant/aspose.slides/portion/getrect/
---
## Portion::GetRect() 方法

取得包圍區段的矩形座標。該矩形包含區段中的所有文字行，亦包括空行。

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

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

## 另請參閱

* 類別 [RectangleF](../../../system.drawing/rectanglef/)
* 類別 [Portion](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)