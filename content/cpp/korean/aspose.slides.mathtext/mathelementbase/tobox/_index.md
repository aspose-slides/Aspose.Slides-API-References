---
title: ToBox()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다. 이 박스는 방정식이나 기타 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다. 박스에 포함된 객체는 (예를 들어) 정렬 포인트가 있거나 없거나 연산자 에뮬레이터 역할을 하거나 줄 바꿈 지점으로 사용되거나, 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다.
type: docs
weight: 261
url: /ko/aspose.slides.mathtext/mathelementbase/tobox/
---
## MathElementBase::ToBox() 메서드

이 요소를 비시각적 박스(논리적 그룹화)에 배치합니다. 이 박스는 수식이나 기타 수학 텍스트 인스턴스의 구성 요소를 그룹화하는 데 사용됩니다. 박스에 포함된 객체는 (예를 들어) 정렬 포인트가 있거나 없거나 연산자 에뮬레이터 역할을 수행하거나 줄 바꿈 지점으로 사용되거나, 줄 바꿈이 허용되지 않도록 그룹화될 수 있습니다.

```cpp
System::SharedPtr<IMathBox> Aspose::Slides::MathText::MathElementBase::ToBox() override
```

### 반환 값

이 요소가 포함된 논리적 박스

## 비고

예시: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBox](../../imathbox/)
* 클래스 [MathElementBase](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)