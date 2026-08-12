---
title: RoundImpl()
second_title: Aspose.Slides C++ API रेफ़रेंस के लिए
description: निर्दिष्ट मान को निर्दिष्ट दशमलव अंकों की संख्या के साथ निकटतम मान तक गोल करता है। एक पैरामीटर यह निर्धारित करता है कि यदि निर्दिष्ट मान दो निकटतम संख्याओं के समान दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होना चाहिए।
type: docs
weight: 287
url: /hi/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) विधि

निर्दिष्ट **value** को निकटतम मान तक गोल करता है, जिसमें निर्दिष्ट दशमलव अंकों की संख्या होती है। एक पैरामीटर यह निर्धारित करता है कि यदि निर्दिष्ट **value** दो निकटतम संख्याओं के समान दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होना चाहिए।

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | **float** | राउंड करने के लिए मान |
| digits | int | राउंड किए गए मान में दशमलव अंकों की संख्या |
| mode | [MidpointRounding](../../midpointrounding/) | यदि **value** दो निकटतम संख्याओं के समान दूरी पर हो तो राउंडिंग कैसे की जाए यह निर्धारित करता है। |

### वापसी मान

निर्दिष्ट अंकों की संख्या वाले वह संख्या जो **value** के सबसे निकट हो।

## संबंधित देखें

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)