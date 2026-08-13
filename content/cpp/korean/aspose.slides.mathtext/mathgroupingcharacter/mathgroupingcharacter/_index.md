---
title: MathGroupingCharacter()
second_title: Aspose.Slides for C++ API 참조
description: MathGroupingCharacter 클래스를 기본 그룹화 문자 U+23DF (BOTTOM CURLY BRACKET) 로 새 인스턴스를 초기화합니다
type: docs
weight: 92
url: /ko/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) 생성자


기본 그룹화 문자 U+23DF (BOTTOM CURLY BRACKET) 로 [MathGroupingCharacter](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 바가 적용되는 기본 요소 |
## 비고



예시: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) 생성자


[MathGroupingCharacter](../) 클래스를 새 인스턴스로 초기화합니다.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 바가 적용되는 기본 요소 |
| character | char16_t | 그룹화 문자 |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | 그룹화 문자의 위치 |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | 그룹 문자의 수직 정렬 |
## 비고



예시: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## 참고

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)