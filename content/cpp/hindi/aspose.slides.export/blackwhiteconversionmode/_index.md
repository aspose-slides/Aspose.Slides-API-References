---
title: BlackWhiteConversionMode
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: विकल्प प्रदान करता है जो नियंत्रित करते हैं कि स्लाइड्स की छवियों को बाइटोनल छवियों में कैसे परिवर्तित किया जाएगा।
type: docs
weight: 820
url: /hi/aspose.slides.export/blackwhiteconversionmode/
---
## BlackWhiteConversionMode enum

स्लाइड्स की छवियों को बाइटोनल छवियों में परिवर्तित करने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

```cpp
enum class BlackWhiteConversionMode
```

### Values

| नाम | मूल्य | विवरण |
| --- | --- | --- |
| Default | 0 | कोई रूपांतरण एल्गोरिथ्म नहीं निर्दिष्ट करता है। TIFF कोडेक में लागू किया गया एल्गोरिथ्म उपयोग किया जाएगा। (Default) |
| Dithering | 1 | डिथरिंग एल्गोरिथ्म (Floyd-Steinberg) निर्दिष्ट करता है। |
| DitheringFloydSteinberg | 2 | Floyd-Steinberg डिथरिंग एल्गोरिथ्म निर्दिष्ट करता है। |
| Auto | 3 | स्वचालित रूप से गणना किए गए थ्रेशहोल्ड एल्गोरिथ्म (Otsu) को निर्दिष्ट करता है। |
| AutoOtsu | 4 | स्वचालित रूप से गणना किए गए Otsu का थ्रेशहोल्ड एल्गोरिथ्म निर्दिष्ट करता है। |
| Threshold25 | 5 | स्थिर थ्रेशहोल्ड एल्गोरिथ्म (25%) को निर्दिष्ट करता है। |
| Threshold50 | 6 | स्थिर थ्रेशहोल्ड एल्गोरिथ्म (50%) को निर्दिष्ट करता है। |
| Threshold75 | 7 | स्थिर थ्रेशहोल्ड एल्गोरिथ्म (75%) को निर्दिष्ट करता है। |

## संबंधित देखें

* नेमस्पेस [Aspose::Slides::Export](../)
* लाइब्रेरी [Aspose.Slides](../../)