---
title: idx_set()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에 IMathElement를 설정합니다.
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathblock/idx_set/
---
## MathBlock::idx_set(int32_t, System::SharedPtr\<IMathElement\>) 메서드

지정된 인덱스에 [IMathElement](../../imathelement/)를 설정합니다.

```cpp
void Aspose::Slides::MathText::MathBlock::idx_set(int32_t index, System::SharedPtr<IMathElement> value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 항목의 0부터 시작하는 인덱스 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 수학 요소. |
## 비고

예시:
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