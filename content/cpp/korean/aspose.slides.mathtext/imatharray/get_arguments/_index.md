---
title: get_Arguments()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 배열의 항목 집합
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() 메서드

배열의 항목 집합

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## 비고

예시: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElementCollection](../../imathelementcollection/)
* 클래스 [IMathArray](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)