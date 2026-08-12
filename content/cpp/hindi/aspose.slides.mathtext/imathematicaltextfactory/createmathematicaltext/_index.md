---
title: CreateMathematicalText()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: खाली गणितीय पाठ तत्व बनाएं
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() method

खाली Mathematical Text तत्व बनाएं

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Return Value

नया Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) method

निर्दिष्ट मान के साथ Mathematical Text तत्व बनाएं

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathSymbol | char16_t | उपयोग करने के लिए एकल प्रतीक |

### Return Value

नया Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) method

निर्दिष्ट मान के साथ खाली Mathematical Text तत्व बनाएं

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | पाठ मान |

### Return Value

नया Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) method

निर्दिष्ट मान और स्वरूपण गुणों के साथ खाली Mathematical Text तत्व बनाएं

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | पाठ मान |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | पाठ स्वरूप सेटिंग्स |

### Return Value

नया Mathematical Text

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathematicalText](../../imathematicaltext/)
* Class [IMathematicalTextFactory](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)