---
title: Insert()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट अनुक्रमांक पर संग्रह में एक गणितीय तत्व सम्मिलित करता है।
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) method


संग्रह में निर्दिष्ट अनुक्रमांक पर एक गणितीय तत्व सम्मिलित करता है।

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | शून्य-आधारित इंडेक्स जिस पर [IMathElement](../../imathelement/) को डालना चाहिए। |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | डालने के लिए [IMathElement](../../imathelement/)। |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathElementCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)