---
title: GetRect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: portion을 둘러싼 사각형의 좌표를 가져옵니다. 이 사각형은 portion의 모든 텍스트 라인을 포함하며, 빈 라인도 포함합니다.
type: docs
weight: 92
url: /ko/aspose.slides/portion/getrect/
---
## Portion::GetRect() 메서드

portion을 둘러싼 사각형의 좌표를 가져옵니다. 이 사각형은 portion의 모든 텍스트 라인을 포함하며, 빈 라인도 포함합니다.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## 비고

예제: 
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

## 참고

* 클래스 [RectangleF](../../../system.drawing/rectanglef/)
* 클래스 [Portion](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)