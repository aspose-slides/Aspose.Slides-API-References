---
title: get_text_boxes_contains_text method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides.util/slideutil/get_text_boxes_contains_text/
weight: 70
---
## get_text_boxes_contains_text(slide, text, check_placeholder_text) {#ibaseslide-str-bool}
निर्दिष्ट स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है जो दिए गए टेक्स्ट को शामिल करते हैं।

### रिटर्न
एक एरे जिसमें [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe) वस्तुएँ हैं जो निर्दिष्ट टेक्स्ट को शामिल करती हैं।

```python
@staticmethod
def get_text_boxes_contains_text(slide, text, check_placeholder_text):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide) | खोज करने के लिए स्लाइड। |
| text | **str** | टेक्स्ट फ्रेमों के भीतर खोजने के लिए टेक्स्ट। |
| check_placeholder_text | **bool** | निर्धारित करता है कि क्या खाली टेक्स्ट फ्रेमों को शामिल किया जाए, लेकिन जिनका प्लेसहोल्डर टेक्स्ट खोज टेक्स्ट को शामिल करता है। |

### संबंधित
* क्लास [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)
* क्लास [`ITextFrame`](/slides/python-net/hi/aspose.slides/itextframe)
* क्लास [`SlideUtil`](/slides/python-net/hi/aspose.slides.util/slideutil)
* मॉड्यूल [`aspose.slides.util`](/slides/python-net/hi/aspose.slides.util)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)