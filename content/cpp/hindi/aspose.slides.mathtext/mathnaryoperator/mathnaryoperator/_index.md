---
title: MathNaryOperator()
second_title: Aspose.Slides for C++ API संदर्भ
description: MathNaryOperator क्लास का एक नया उदाहरण प्रारम्भ करता है।
type: docs
weight: 183
url: /hi/aspose.slides.mathtext/mathnaryoperator/mathnaryoperator/
---
## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) निर्माता


[MathNaryOperator](../) क्लास का एक नया उदाहरण प्रारम्भ करता है।

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary operator symbol |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upper limit |
## टिप्पणी



उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i=0"), System::MakeObject<MathematicalText>(u"\U0001d465"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) निर्माता


[MathNaryOperator](../) क्लास का एक नया उदाहरण प्रारम्भ करता है।

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary operator symbol |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Lower limit |
## टिप्पणी



उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) निर्माता


[MathNaryOperator](../) क्लास का एक नया उदाहरण प्रारम्भ करता है।

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char16_t | Nary operator symbol |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base argument |
## टिप्पणी



उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"));
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathNaryOperator](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)