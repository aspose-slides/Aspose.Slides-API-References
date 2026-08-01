---
title: MathNaryOperator()
second_title: Aspose.Slides voor C++ API-referentie
description: Initialiseert een nieuw exemplaar van de MathNaryOperator klasse.
type: docs
weight: 183
url: /nl/aspose.slides.mathtext/mathnaryoperator/mathnaryoperator/
---
## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Initialiseert een nieuwe instantie van de [MathNaryOperator](../) klasse.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary-operator symbool |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ondergrens |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bovengrens |
## Opmerkingen



Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i=0"), System::MakeObject<MathematicalText>(u"\U0001d465"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Initialiseert een nieuwe instantie van de [MathNaryOperator](../) klasse.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary-operator symbool |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ondergrens |
## Opmerkingen



Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) constructor

Initialiseert een nieuwe instantie van de [MathNaryOperator](../) klasse.

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary-operator symbool |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basisargument |
## Opmerkingen



Voorbeeld: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"));
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathNaryOperator](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)