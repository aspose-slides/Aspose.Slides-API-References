---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에서 IMathElement를 가져옵니다.
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) 메서드


지정된 인덱스에서 [IMathElement](../../imathelement/)를 가져옵니다.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 항목의 0부터 시작하는 인덱스 |

### 반환 값

수학 요소.

## 비고



예제: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)