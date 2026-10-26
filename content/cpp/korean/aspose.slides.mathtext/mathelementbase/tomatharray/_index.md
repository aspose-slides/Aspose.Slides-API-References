---
title: ToMathArray()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수직 배열에 넣습니다
type: docs
weight: 170
url: /ko/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() 메서드


수직 배열에 넣습니다

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### 반환값

새 인스턴스 유형 [IMathArray](../../imatharray/)
## 비고



예제: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathArray](../../imatharray/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)