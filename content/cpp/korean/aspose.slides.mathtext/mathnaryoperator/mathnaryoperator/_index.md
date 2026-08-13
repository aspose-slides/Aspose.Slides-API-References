---
title: MathNaryOperator()
second_title: Aspose.Slides for C++ API 참조
description: MathNaryOperator 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 183
url: /ko/aspose.slides.mathtext/mathnaryoperator/mathnaryoperator/
---
## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


[MathNaryOperator](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary 연산자 기호 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 기본 인수 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 하한 |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 상한 |
## 비고



예: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i=0"), System::MakeObject<MathematicalText>(u"\U0001d465"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


[MathNaryOperator](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary 연산자 기호 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 기본 인수 |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 하한 |
## 비고



예: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) constructor


[MathNaryOperator](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary 연산자 기호 |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 기본 인수 |
## 비고



예: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"));
```

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathNaryOperator](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)