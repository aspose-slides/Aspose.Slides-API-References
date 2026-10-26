---
title: ToMathArray()
second_title: Aspose.Slides C++ API 레퍼런스
description: 자식 요소를 수직 배열에 배치합니다
type: docs
weight: 235
url: /ko/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() 메서드


자식 요소를 수직 배열에 배치합니다

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### 반환 값

새 인스턴스 유형 [IMathArray](../../imatharray/)
## 비고



예: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## 또 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathArray](../../imatharray/)
* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)