---
title: GetRect()
second_title: Aspose.Slides for C++ API リファレンス
description: portion を囲む rect の座標を取得します。rect には、portion 内のすべてのテキスト行（空行も含む）が含まれます。
type: docs
weight: 92
url: /ja/aspose.slides/portion/getrect/
---
## Portion::GetRect() メソッド

portion を囲む rect の座標を取得します。rect は portion 内のすべてのテキスト行（空行も含む）を含みます。

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## 備考

例:
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

## 参照

* クラス [RectangleF](../../../system.drawing/rectanglef/)
* クラス [Portion](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)