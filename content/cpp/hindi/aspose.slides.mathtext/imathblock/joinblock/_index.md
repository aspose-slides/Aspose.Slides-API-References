---
title: JoinBlock()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक अन्य गणितीय ब्लॉक को इस ब्लॉक के साथ जोड़ता है
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathblock/joinblock/
---
## IMathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) मेथड

एक अन्य गणितीय ब्लॉक को इस ब्लॉक के साथ जोड़ता है

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlock::JoinBlock(System::SharedPtr<IMathBlock> other)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../)\> | जोड़ने वाला ब्लॉक |

### रिटर्न वैल्यू

जोड़ने के बाद यह गणितीय ब्लॉक

## टिप्पणी



उदाहरण: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"c"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"a"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)