---
title: MathNaryOperator()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av MathNaryOperator-klassen.
type: docs
weight: 183
url: /sv/aspose.slides.mathtext/mathnaryoperator/mathnaryoperator/
---
## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktor

Initierar en ny instans av [MathNaryOperator](../) klass.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary-operator symbol |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basargument |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Undre gräns |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Övre gräns |
## Anmärkningar

Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i=0"), System::MakeObject<MathematicalText>(u"\U0001d465"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) konstruktor

Initierar en ny instans av [MathNaryOperator](../) klass.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary-operator symbol |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basargument |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Undre gräns |
## Anmärkningar

Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) konstruktor

Initierar en ny instans av [MathNaryOperator](../) klass.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary-operator symbol |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basargument |
## Anmärkningar

Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathNaryOperator](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)