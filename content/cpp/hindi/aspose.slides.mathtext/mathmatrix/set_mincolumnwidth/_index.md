---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API संदर्भ
description: "ट्विप्स (1/20 बिंदु) में न्यूनतम कॉलम चौड़ाई। गैप स्पेसिंग (जिसे \\u201CColumn Gap\\u201D या \\u201CGap Width\\u201D भी कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स कॉलम स्पेसिंग (विभिन्न कॉलमों के समान किनारों के बीच की दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0."
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) विधि


ट्विप्स (1/20th of a point) में न्यूनतम कॉलम चौड़ाई। गैप स्पेसिंग (जिसे \\u201CColumn Gap\\u201D या \\u201CGap Width\\u201D भी कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स [Column](../../../aspose.slides/column/) स्पेसिंग (विभिन्न कॉलमों के समान किनारों के बीच की दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0.

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## संबंधित देखें

* क्लास [MathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)