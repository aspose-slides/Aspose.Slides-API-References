---
title: MathRadical()
second_title: Aspose.Slides for C++ API 참조
description: MathRadical 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) 생성자

새로운 [MathRadical](../) 클래스의 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 기본 |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 지수 |

## 비고

예:
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathRadical](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)