---
title: RemoveAt()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सूची में निर्दिष्ट अनुक्रमणिका पर FallBack फ़ॉन्ट को हटाता है।
type: docs
weight: 131
url: /hi/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) विधि


फ़ॉन्ट सूची में निर्दिष्ट अनुक्रमणिका पर FallBack फ़ॉन्ट को हटाता है।

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | **int32_t** | हटाने के लिए फ़ॉन्ट की शून्य-आधारित अनुक्रमणिका। |
## टिप्पणियाँ



```cpp
// एक नियम बनाता है जिसमें फ़ॉन्ट्स की सूची होती है।
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// सूची से Tahoma को हटाता है।
newRule->RemoveAt(2);
```


## संबंधित देखें

* वर्ग [FontFallBackRule](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)