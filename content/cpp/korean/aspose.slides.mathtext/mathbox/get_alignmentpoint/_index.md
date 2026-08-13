---
title: get_AlignmentPoint()
second_title: C++용 Aspose.Slides API 참조
description: "true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에서 지정된 정렬 지점과 정렬될 수 있습니다. 기본값: false"
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() 메서드


true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식의 지정된 정렬 지점과 정렬될 수 있습니다. 기본값: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## 비고


예: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 참조

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)