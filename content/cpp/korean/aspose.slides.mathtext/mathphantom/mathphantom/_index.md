---
title: MathPhantom()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 기본 수학 요소를 사용하여 MathPhantom 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) 생성자


지정된 기본 수학 요소를 사용하여 [MathPhantom](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 팬텀에 의해 가시성 및 레이아웃이 제어되는 기본 [IMathElement](../../imathelement/). 이 요소는 숨겨지거나 표시될 수 있는 콘텐츠를 정의하지만, 주변 수학의 기하학적 정렬에 여전히 영향을 미칩니다. |

## 참고

팬텀 요소는 기본 표현식의 시각적 공간을 반드시 표시하지 않고도 예약하거나 억제하는 데 사용됩니다. 이는 OMML 요소 **<m:phant>**에 해당합니다.

예시:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathPhantom](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)