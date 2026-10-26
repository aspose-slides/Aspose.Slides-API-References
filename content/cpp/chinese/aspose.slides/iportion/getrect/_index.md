---
title: GetRect()
second_title: Aspose.Slides for C++ API 参考
description: 获取限定部分的矩形坐标。该矩形包括部分中的所有文本行，包括空行。
type: docs
weight: 79
url: /zh/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() 方法

获取限定部分的矩形坐标。该矩形包括部分中的所有文本行，包括空行。

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```

### 返回值

限定部分的矩形 [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## 备注

示例：
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

## 另见

* 类 [RectangleF](../../../system.drawing/rectanglef/)
* 类 [IPortion](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)