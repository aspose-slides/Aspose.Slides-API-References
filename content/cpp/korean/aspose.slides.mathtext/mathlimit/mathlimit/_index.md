---
title: MathLimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: MathLimit 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/mathlimit/mathlimit/
---
## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) 생성자

새로운 [MathLimit](../) 클래스의 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)
```

## 비고

예제:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"), false);
```

## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 생성자

새로운 [MathLimit](../) 클래스를 하한과 함께 초기화합니다.

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)
```

## 비고

예제:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"));
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathLimit](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)