---
title: ToBox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 요소를 비시각적 상자(논리적 그룹화)에 배치합니다. 이 상자는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 박스 객체는 (예를 들어) 정렬 지점이 있든 없든 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 내부에서 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다.
type: docs
weight: 274
url: /ko/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() 메서드

이 요소를 비시각적 상자에 배치합니다(논리적 그룹화). 이 상자는 방정식이나 기타 수학 텍스트의 구성 요소를 그룹화하는 데 사용됩니다. 박스 객체는 (예를 들어) 정렬 지점이 있든 없든 연산자 에뮬레이터 역할을 하거나, 줄 바꿈 지점으로 사용되거나, 줄 바꿈을 허용하지 않도록 그룹화될 수 있습니다.

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```

### 반환 값

이 요소가 내부에 배치된 논리적 상자

## 비고

예:
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBox](../../imathbox/)
* 클래스 [IMathElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)