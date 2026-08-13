---
title: set_ExplicitBreak()
second_title: Aspose.Slides C++용 API 참고문서
description: "명시적 줄 바꿈은 Box 객체의 시작 부분에 줄 바꿈이 있는지를 지정하며, 이를 통해 라인이 Box 객체의 시작 부분에서 래핑됩니다. 이전 수학 텍스트 라인의 연산자 번호를 지정하여 현재 수학 텍스트 라인의 정렬점으로 사용합니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음)"
type: docs
weight: 131
url: /ko/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) 메서드


명시적 줄 바꿈은 Box 개체의 시작 부분에 줄 바꿈이 있는지를 지정하며, 이렇게 하면 라인이 Box 개체의 시작 부분에서 래핑됩니다. 이전 수학 텍스트 라인의 연산자 번호를 지정하며, 해당 번호는 현재 수학 텍스트 라인의 정렬점으로 사용됩니다. 가능한 값: 1..255 기본값: 0 (명시적 줄 바꿈 없음)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
```

## 비고


예시: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## 참조

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)