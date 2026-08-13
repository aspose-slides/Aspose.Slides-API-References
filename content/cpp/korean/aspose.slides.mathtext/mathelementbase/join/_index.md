---
title: Join()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 요소를 결합하고 수학 블록을 형성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) 메서드

수학 요소를 결합하고 수학 블록을 형성합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 결합할 요소 |

### 반환 값

이 인스턴스와 지정된 인수를 포함하는 새로운 [IMathBlock](../../imathblock/)

## 비고



예: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) 메서드

수학 텍스트를 결합하고 수학 블록을 형성합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 결합할 수학 텍스트 |

### 반환 값

이 인스턴스와 지정된 인수를 포함하는 새로운 [IMathBlock](../../imathblock/)

## 비고



예: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 또 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathElementBase](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)