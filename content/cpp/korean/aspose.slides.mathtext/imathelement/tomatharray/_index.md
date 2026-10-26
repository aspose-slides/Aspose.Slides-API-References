---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 참조
description: 수직 배열에 넣습니다
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() 메서드

수직 배열에 넣습니다

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```

### 반환값

[IMathArray](../../imatharray/) 유형의 새 인스턴스

## 비고



예제:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathArray](../../imatharray/)
* 클래스 [IMathElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)