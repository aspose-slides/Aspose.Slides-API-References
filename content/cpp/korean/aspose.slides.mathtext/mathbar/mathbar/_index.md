---
title: MathBar()
second_title: Aspose.Slides for C++ API 레퍼런스
description: MathBar를 오버바(상단 위치)와 함께 초기화합니다
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) 생성자

[MathBar](../)를 위바(상단 위치)와 함께 초기화합니다

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 바가 적용되는 기본 요소 |
## 비고

예:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) 생성자

[MathBar](../)를 지정된 위치와 함께 초기화합니다

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 바가 적용되는 기본 요소 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 바 라인의 위치 |
## 비고

예:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## 참조

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBar](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)