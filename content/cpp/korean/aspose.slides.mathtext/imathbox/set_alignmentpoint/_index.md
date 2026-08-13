---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API 참조
description: "true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 식에 지정된 정렬 지점들을 이와 정렬할 수 있습니다. 기본값: false"
type: docs
weight: 105
url: /ko/aspose.slides.mathtext/imathbox/set_alignmentpoint/
---
## IMathBox::set_AlignmentPoint(bool) method

true일 때, 이 연산자 에뮬레이터는 정렬 지점 역할을 하며, 다른 식에 지정된 정렬 지점들을 이와 정렬할 수 있습니다. 기본값: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_AlignmentPoint(bool value)=0
```

## 비고

예:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 참고

* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)