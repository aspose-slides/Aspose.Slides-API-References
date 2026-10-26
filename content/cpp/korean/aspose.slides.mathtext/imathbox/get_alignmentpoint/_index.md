---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 식에 지정된 정렬 지점들을 이를 기준으로 정렬할 수 있습니다. 기본값: false"
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() 메서드


true인 경우, 이 연산자 에뮬레이터는 정렬 지점으로 작동합니다; 즉, 다른 식에 지정된 정렬 지점들을 이를 기준으로 정렬할 수 있습니다. 기본값: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## 비고


예:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 참조

* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)