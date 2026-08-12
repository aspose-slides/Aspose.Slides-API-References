---
title: GetVisualBounds()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: रेंडर की गई सामग्री से गणना किए गए shape की दृश्य सीमाओं को प्राप्त करता है।
type: docs
weight: 677
url: /hi/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() विधि

रेंडर की गई सामग्री से गणना किए गए shape की दृश्य सीमाओं को प्राप्त करता है।

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### Return Value

एक [System::Drawing::RectangleF](../../../system.drawing/rectanglef/) जो slide निर्देशांक में shape की दृश्य सीमाओं को दर्शाता है।

## Remarks

वापसी किया गया आयत सभी सामग्री की अक्ष-समतल सीमाओं को दर्शाता है जो shape द्वारा rendering के दौरान slide निर्देशांक स्थान में उत्पन्न होती हैं।

ये सीमाएँ shape के मॉडल सीमाओं ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) से भिन्न हो सकती हैं और यदि रेंडर की गई सामग्री slide मूल बिंदु से परे विस्तारित होती है तो नकारात्मक निर्देशांक भी हो सकते हैं।

विज़ुअल बाउंड्स रेंडरिंग संबंधित पहलुओं को ध्यान में रखती हैं जैसे परिवर्तन (उदाहरण के लिए, घुमाव), स्ट्रोक चौड़ाई और जॉइन, टेक्स्ट लेआउट और ओवरफ़्लो, [SmartArt](../../../aspose.slides.smartart/) ज्यामिति, और अन्य लेआउट प्रभाव जो shape की अंतिम रेंडर दिखावट को प्रभावित करते हैं।

वापसी की गई सीमाएँ slide आयत में क्लिप नहीं की गई हैं।

## See Also

* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Shape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)