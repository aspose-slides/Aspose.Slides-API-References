---
title: Round()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट मान को निकटतम पूर्णांक संख्या पर गोल करता है। एक पैरामीटर निर्दिष्ट करता है कि यदि निर्दिष्ट मान दो निकटतम संख्याओं के समान दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा।
type: docs
weight: 404
url: /hi/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) विधि


निर्दिष्ट मान को निकटतम पूर्णांक संख्या पर गोल करता है। एक पैरामीटर निर्दिष्ट करता है कि यदि निर्दिष्ट मान दो निकटतम संख्याओं के समान दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा।

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| d | const [Decimal](../)\& | राउंड करने वाला मान |
| mode | [MidpointRounding](../../midpointrounding/) | यदि **value** दो निकटतम संख्याओं के समान दूरी पर हो तो राउंडिंग कैसे की जाती है, यह निर्दिष्ट करता है। |

### वापसी मान

**d** को निकटतम पूर्णांक मान पर गोल किया गया

## Decimal::Round(const Decimal\&, int, MidpointRounding) विधि


निर्दिष्ट मान को निर्दिष्ट अंकों की संख्या के साथ निकटतम मान पर गोल करता है। एक पैरामीटर निर्दिष्ट करता है कि यदि निर्दिष्ट मान दो निकटतम संख्याओं के समान दूरी पर हो तो फ़ंक्शन का व्यवहार क्या होगा।

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| d | const [Decimal](../)\& | राउंड करने वाला मान |
| digits | int | गोल किए गए मान में अंकों की संख्या |
| mode | [MidpointRounding](../../midpointrounding/) | यदि **value** दो निकटतम संख्याओं के समान दूरी पर हो तो राउंडिंग कैसे की जाती है, यह निर्दिष्ट करता है। |

### वापसी मान

निर्दिष्ट अंकों की संख्या के साथ **value** के निकटतम संख्या

## संबंधित देखें

* एन्यूम [MidpointRounding](../../midpointrounding/)
* क्लास [Decimal](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)