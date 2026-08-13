---
title: Join()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 수학 블록에 수학 요소를 연결합니다
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) 메서드

이 수학 블록에 수학 요소를 연결합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 연결할 요소 |

### 반환값

현재 [IMathBlock](../../imathblock/) 인스턴스

## 참고

예시: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) 메서드

이 수학 블록에 수학 텍스트를 연결합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 연결할 수학 텍스트 |

### 반환값

이 인스턴스와 지정된 인수를 포함하는 새로운 [IMathBlock](../../imathblock/)

## 참고

예시: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBlock](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)