---
title: MultiplyTransform()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को निर्दिष्ट मैट्रिक्स द्वारा गुणा करता है।
type: docs
weight: 430
url: /hi/system.drawing/pen/multiplytransform/
---
## Pen::MultiplyTransform(const SharedPtr\<Drawing2D::Matrix\>\&, Drawing2D::MatrixOrder) विधि

वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को निर्दिष्ट मैट्रिक्स से गुणा करता है।

```cpp
void System::Drawing::Pen::MultiplyTransform(const SharedPtr<Drawing2D::Matrix> &matrix, Drawing2D::MatrixOrder order=Drawing2D::MatrixOrder::Prepend)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| matrix | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::Matrix](../../../system.drawing.drawing2d/matrix/)\>\& | वह मैट्रिक्स जिससे वर्तमान ऑब्जेक्ट की ट्रांसफ़ॉर्म मैट्रिक्स को गुणा किया जाता है |
| order | [Drawing2D::MatrixOrder](../../../system.drawing.drawing2d/matrixorder/) | ऑपरेशन के क्रम को निर्दिष्ट करता है |

## संबंधित देखें

* एन्यूम [MatrixOrder](../../../system.drawing.drawing2d/matrixorder/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [Matrix](../../../system.drawing.drawing2d/matrix/)
* क्लास [Pen](../)
* नेमस्पेस [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)