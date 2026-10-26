---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈 수학 텍스트 요소를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() 메서드

Create empty mathematical text element

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```

### 반환 값

새로운 Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) 메서드

Create mathematical text element with the specified value

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathSymbol | char16_t | 텍스트 값으로 사용할 단일 기호 |

### 반환 값

새로운 Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) 메서드

Create empty mathematical text element with the specified value

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 텍스트 값 |

### 반환 값

새로운 Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 메서드

Create empty mathematical text element with the specified value and formatting properties

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 텍스트 값 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 텍스트 서식 설정 |

### 반환 값

새로운 Mathematical Text

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathematicalText](../../imathematicaltext/)
* 클래스 [MathematicalTextFactory](../)
* 클래스 [String](../../../system/string/)
* 클래스 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)