---
title: RemoveAt()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट सूचकांक पर संग्रह में तत्व को हटाता है।
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) मेथड


संग्रह में निर्दिष्ट सूचकांक पर स्थित तत्व को हटाता है।

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | हटाने वाले तत्व का शून्य-आधारित सूचकांक। |
## टिप्पणी



उदाहरण: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## देखें

* क्लास [IMathElementCollection](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)