---
title: MathBar()
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: ओवरबार (ऊपरी स्थिति) के साथ MathBar को प्रारंभ करता है
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathbar/mathbar/
---
## MathBar::MathBar(System::SharedPtr\<IMathElement\>) कंस्ट्रक्टर


ओवरबार (ऊपरी स्थिति) के साथ [MathBar](../) को प्रारंभ करता है

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बार लागू करने वाले बेस एलिमेंट |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBar::MathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) कंस्ट्रक्टर


निर्दिष्ट स्थिति के साथ [MathBar](../) को प्रारंभ करता है

```cpp
Aspose::Slides::MathText::MathBar::MathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | बार लागू करने वाले बेस एलिमेंट |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | बार लाइन की स्थिति। |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"), MathTopBotPositions::Bottom);
```

## देखें

* एन्युम [MathTopBotPositions](../../mathtopbotpositions/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathBar](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)