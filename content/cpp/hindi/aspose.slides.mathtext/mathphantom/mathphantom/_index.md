---
title: MathPhantom()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट बेस गणित तत्व का उपयोग करके MathPhantom क्लास का एक नया उदाहरण प्रारंभ करता है।
type: docs
weight: 144
url: /hi/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) निर्माता

निर्दिष्ट बेस गणित तत्त्व का उपयोग करके [MathPhantom](../) क्लास का नया उदाहरण प्रारंभ करता है।

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | वह बेस [IMathElement](../../imathelement/) जिसका दृश्य और लेआउट फ़ैंटम द्वारा नियंत्रित किया जाएगा। यह तत्व वह सामग्री परिभाषित करता है जिसे छिपाया या दिखाया जा सकता है, जबकि फिर भी आसपास की गणितीय व्यवस्था पर प्रभाव डालता है। |

## टिप्पणी

फ़ैंटम एलेमेंट का उपयोग उसके बेस अभिव्यक्ति की दृश्य जगह को आरक्षित या दमन करने के लिए किया जाता है, बिना आवश्यक रूप से उसे प्रदर्शित किए। यह OMML एलेमेंट **<m:phant>** के अनुरूप है।

उदाहरण:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathPhantom](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)