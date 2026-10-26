---
title: GetRect()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 부분을 둘러싸는 사각형의 좌표를 가져옵니다. 이 사각형에는 빈 줄을 포함한 부분의 모든 텍스트 줄이 포함됩니다.
type: docs
weight: 79
url: /ko/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() 메서드


부분을 둘러싸는 사각형의 좌표를 가져옵니다. 이 사각형에는 빈 줄을 포함한 부분의 모든 텍스트 줄이 포함됩니다.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### 반환값

Rectangle 부분을 둘러싸는 [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## 비고



예:
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

## 참조

* 클래스 [RectangleF](../../../system.drawing/rectanglef/)
* 클래스 [IPortion](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)