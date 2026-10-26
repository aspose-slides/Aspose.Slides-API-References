---
title: Remove()
second_title: Aspose.Slides for C++ API संदर्भ
description: एक विशिष्ट वस्तु की पहली उपस्थिति को संग्रह से हटाता है।
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) मेथड


संग्रह से किसी विशिष्ट वस्तु की पहली उपस्थिति को हटाता है।

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | संग्रह से हटाने के लिए वस्तु। |

### वापसी मान

true यदि *item* को संग्रह से सफलतापूर्वक हटाया गया; अन्यथा, false. यह मेथड भी false लौटाता है यदि *item* मूल संग्रह में नहीं मिला।

## टिप्पणी



उदाहरण: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## देखें भी

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathElementCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)