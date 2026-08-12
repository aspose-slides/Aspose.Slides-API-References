---
title: MathBlock()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: MathBlock क्लास का नया उदाहरण आरंभ करता है।
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() कंस्ट्रक्टर

[MathBlock](../) क्लास का नया उदाहरण प्रारंभ करता है।

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## टिप्पणी

उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) कंस्ट्रक्टर

एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्व उसमें रखता है।

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ब्लॉक में रखने के लिए गणितीय तत्व |

## टिप्पणी



उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) कंस्ट्रक्टर

एक नया गणितीय ब्लॉक बनाता है और निर्दिष्ट तत्वों को उसमें रखता है।

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | ब्लॉक में रखने के लिए गणितीय तत्वों |

## टिप्पणी



उदाहरण: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [MathBlock](../)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IEnumerable](../../../system.collections.generic/ienumerable/)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)