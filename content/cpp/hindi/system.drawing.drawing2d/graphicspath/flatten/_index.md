---
title: Flatten()
second_title: Aspose.Slides for C++ API संदर्भ
description: पथ में प्रत्येक वक्र को जुड़ी हुई रेखाओं की श्रृंखला में बदलकर सपाट करता है। 0.25 का फ्लैटनेस मान उपयोग किया जाता है।
type: docs
weight: 391
url: /hi/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() विधि

पथ में प्रत्येक वक्र को जुड़ी हुई रेखाओं की श्रृंखला में बदलकर सपाट किया जाता है। 0.25 की फ्लैटनेस मान का उपयोग किया जाता है।

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) विधि

पथ में प्रत्येक वक्र को जुड़ी हुई रेखाओं की श्रृंखला में बदलकर सपाट किया जाता है। 0.25 की फ्लैटनेस मान का उपयोग किया जाता है।

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | सपाट करने से पहले पथ पर लागू करने के लिए ट्रांसफ़ॉर्म मैट्रिक्स |

## GraphicsPath::Flatten(const MatrixPtr\&, float) विधि

पथ में प्रत्येक वक्र को जुड़ी हुई रेखाओं की श्रृंखला में बदलकर सपाट किया जाता है।

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### तर्क

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | सपाट करने से पहले पथ पर लागू करने के लिए ट्रांसफ़ॉर्म मैट्रिक्स |
| flatness | **float** | वक्र और उसके सपाट अनुमान के बीच अधिकतम अनुमति त्रुटि निर्धारित करता है |

## संबंधित देखें

* टाइपडिफ [MatrixPtr](../../matrixptr/)
* क्लास [GraphicsPath](../)
* नामस्थान [System::Drawing::Drawing2D](../../)
* लाइब्रेरी [Aspose.Slides](../../../)