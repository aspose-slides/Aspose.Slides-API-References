---
title: set_ExplicitBreak()
second_title: Aspose.Slides for C++ API 참조
description: "Explicit break는 Box 객체의 시작에 줄 바꿈이 있는지 여부를 지정합니다. 즉, 줄이 Box 객체의 시작에서 래핑됩니다. 이전 수학 텍스트 줄에 있는 연산자 번호를 지정하며, 이는 현재 수학 텍스트 줄의 정렬 기준점으로 사용됩니다. 가능한 값: 1..255 기본값: 0 (no explicit break)"
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) 메서드


Explicit break는 Box 객체의 시작에 줄 바꿈이 있는지 여부를 지정합니다. 즉, 줄이 Box 객체의 시작에서 래핑됩니다. 이전 줄의 수학 텍스트에 있는 연산자의 번호를 지정하며, 이는 현재 줄의 수학 텍스트 정렬 기준점으로 사용됩니다. 가능한 값: 1..255 기본값: 0 (no explicit break)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
```

## 비고


예시: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 참고

* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)