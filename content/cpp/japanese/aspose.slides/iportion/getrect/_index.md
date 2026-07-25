---
title: GetRect()
second_title: Aspose.Slides for C++ API リファレンス
description: 部分を囲む矩形の座標を取得します。矩形には、空の行を含む、部分内のすべてのテキスト行が含まれます。
type: docs
weight: 79
url: /ja/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() メソッド

部分を囲む矩形の座標を取得します。矩形には、空の行を含む、部分内のすべてのテキスト行が含まれます。

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```

### 戻り値

Rectangle 部分を囲む [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)

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

## 関連項目

* クラス [RectangleF](../../../system.drawing/rectanglef/)
* クラス [IPortion](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)