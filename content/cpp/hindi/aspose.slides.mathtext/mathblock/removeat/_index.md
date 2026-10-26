---
title: RemoveAt()
second_title: Aspose.Slides for C++ API संदर्भ
description: संग्रह में निर्दिष्ट अनुक्रमणिका पर स्थित तत्व को हटाता है।
type: docs
weight: 170
url: /hi/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) विधि

संग्रह में निर्दिष्ट अनुक्रमणिका पर स्थित तत्व को हटाता है।

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | हटाए जाने वाले तत्व का शून्य-आधारित अनुक्रमणिका। |
## टिप्पणियाँ



उदाहरण: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## संबंधित

* क्लास [MathBlock](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)