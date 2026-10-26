---
title: MathBox()
second_title: Aspose.Slides for C++ API 참조
description: MathBox를 지정된 요소를 인수로 사용하여 초기화합니다
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) 생성자


[MathBox](../)를 지정된 요소를 인수로 사용하여 초기화합니다

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 상자를 적용하는 기본 요소입니다. null일 수 있습니다. |
## 비고



예: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)