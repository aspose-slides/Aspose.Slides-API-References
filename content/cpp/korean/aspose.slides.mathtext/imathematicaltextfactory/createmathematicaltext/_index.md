---
title: CreateMathematicalText()
second_title: Aspose.Slides for C++ API 참조
description: 빈 수학 텍스트 요소를 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() 메서드

Create empty Mathematical Text element

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### 반환 값

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) 메서드

Create Mathematical Text element with the specified value

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathSymbol | char16_t | 텍스트 값으로 사용할 단일 기호 |

### 반환 값

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) 메서드

Create empty Mathematical Text element with the specified value

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 텍스트 값 |

### 반환 값

new Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 메서드

Create empty Mathematical Text element with the specified value and formatting properties

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 텍스트 값 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 텍스트 서식 설정 |

### 반환 값

new Mathematical Text

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathematicalText](../../imathematicaltext/)
* 클래스 [IMathematicalTextFactory](../)
* 클래스 [String](../../../system/string/)
* 클래스 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)