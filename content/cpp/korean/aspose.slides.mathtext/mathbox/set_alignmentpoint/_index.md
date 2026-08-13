---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "true일 때, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에 지정된 정렬 지점을 이와 정렬할 수 있습니다. 기본값: false"
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) 메서드

true일 때, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 방정식에 지정된 정렬 지점을 이와 정렬할 수 있습니다. 기본값: false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
```

## 비고

예:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 참고

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)