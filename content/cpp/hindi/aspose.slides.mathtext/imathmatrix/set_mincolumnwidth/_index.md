---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API संदर्भ
description: "ट्विप्स में न्यूनतम कॉलम चौड़ाई (1/20वां पॉइंट) गैप स्पेसिंग (जिसे \\u201CColumn Gap\\u201D या \\u201CGap Width\\u201D भी कहा जाता है) को MinColumnWidth में जोड़कर कुल Matrix Column Spacing (विभिन्न कॉलमों के समान किनारों के बीच की दूरी) निर्धारित किया जाता है। डिफ़ॉल्ट: 0."
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) विधि

न्यूनतम कॉलम चौड़ाई ट्विप्स में (1/20th of a point) गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” भी कहा जाता है) को MinColumnWidth में जोड़कर कुल Matrix [Column](../../../aspose.slides/column/) स्पेसिंग (विभिन्न कॉलमों के समान किनारों के बीच की दूरी) निर्धारित किया जाता है। डिफ़ॉल्ट: 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## टिप्पणी

उदाहरण: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## संबंधित देखें

* क्लास [IMathMatrix](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)