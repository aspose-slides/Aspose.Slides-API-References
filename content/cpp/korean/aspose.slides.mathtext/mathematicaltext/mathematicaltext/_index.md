---
title: MathematicalText()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "기본 생성자 (String::Empty 값을 생성)"
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() 생성자

기본 생성자 (String::Empty 값을 생성)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## 비고

예시: 
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) 생성자

단일 기호로 [MathText](../../)를 생성

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathSymbol | char16_t | 단일 기호 |
## 비고

예시: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) 생성자

텍스트를 사용해 [MathematicalText](../)를 생성

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 텍스트 값 |
## 비고

예시: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) 생성자

텍스트와 포맷 설정을 사용해 [MathematicalText](../)를 생성

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | 텍스트 값 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | 텍스트 형식 설정 |
## 비고

예시: 
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [MathematicalText](../)
* 클래스 [String](../../../system/string/)
* 클래스 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)