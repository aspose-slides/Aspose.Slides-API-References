---
title: equals method
second_title: Aspose.Slides के लिए Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/layoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Determines whether the two IBaseSlide instances are equal.
            Returning value is calculated based on slide's structure and static content.
            Two slides are equal if all shapes, styles, texts, animation and other settings. etc. are equal. The comparison doesn't take into account unique identifier values, e.g. SlideId and dynamic content, e.g. current date value in Date Placeholder.

### वापसी

**true**  यदि निर्दिष्ट IBaseSlide वर्तमान IBaseSlide के बराबर है; 
            अन्यथा, **false** .

```python
def equals(self, slide):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide) | वर्तमान IBaseSlide के साथ तुलना करने के लिए IBaseSlide। |

### संबंधित देखें
* क्लास [`IBaseSlide`](/slides/python-net/hi/aspose.slides/ibaseslide)
* क्लास [`LayoutSlide`](/slides/python-net/hi/aspose.slides/layoutslide)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)