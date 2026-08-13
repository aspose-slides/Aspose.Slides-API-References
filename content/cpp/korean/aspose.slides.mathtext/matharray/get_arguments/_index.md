---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 배열의 항목 집합
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() 메서드


배열의 항목 집합

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## 비고


예제: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElementCollection](../../imathelementcollection/)
* 클래스 [MathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)