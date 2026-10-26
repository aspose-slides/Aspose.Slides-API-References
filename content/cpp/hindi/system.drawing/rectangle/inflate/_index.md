---
title: Inflate()
second_title: Aspose.Slides for C++ API संदर्भ
description: वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए rectangle की चौड़ाई और ऊँचाई को बढ़ाता है, rectangle के ज्यामितीय केंद्र के स्थान को बनाए रखते हुए। चौड़ाई और ऊँचाई दोनों दिशाओं में निर्दिष्ट मात्रा से बढ़ाई जाती हैं।
type: docs
weight: 261
url: /hi/system.drawing/rectangle/inflate/
---
## Rectangle::Inflate(int, int) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए rectangle की चौड़ाई और ऊँचाई को बढ़ाता है, rectangle के ज्यामितीय केंद्र के स्थान को बनाए रखते हुए। चौड़ाई और ऊँचाई दोनों दिशाओं में निर्दिष्ट मात्रा से बढ़ाई जाती है।

```cpp
void System::Drawing::Rectangle::Inflate(int width, int height)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | वह मात्रा जिससे rectangle की width दोनों दिशाओं में बढ़ाई जाएगी |
| height | int | वह मात्रा जिससे rectangle की height दोनों दिशाओं में बढ़ाई जाएगी |

## Rectangle::Inflate(const Size\&) विधि

वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए rectangle की चौड़ाई और ऊँचाई को बढ़ाता है, rectangle के ज्यामितीय केंद्र के स्थान को बनाए रखते हुए। चौड़ाई और ऊँचाई दोनों दिशाओं में निर्दिष्ट आकार ऑब्जेक्ट के width और height मानों के अनुसार बढ़ाई जाती है।

```cpp
void System::Drawing::Rectangle::Inflate(const Size &size)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| size | const [Size](../../size/)\& | वह [Size](../../size/) ऑब्जेक्ट जो rectangle की width और height को बढ़ाने की मात्रा निर्दिष्ट करता है |

## Rectangle::Inflate(const Rectangle\&, int, int) विधि

निर्दिष्ट ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए rectangle की चौड़ाई और ऊँचाई को बढ़ाता है, rectangle के ज्यामितीय केंद्र के स्थान को बनाए रखते हुए। चौड़ाई और ऊँचाई दोनों दिशाओं में निर्दिष्ट मात्रा से बढ़ाई जाती है।

```cpp
static Rectangle System::Drawing::Rectangle::Inflate(const Rectangle &rect, int x, int y)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | inflate करने के लिये rectangle |
| x | int | वह मात्रा जिससे rectangle की width दोनों दिशाओं में बढ़ाई जाएगी |
| y | int | वह मात्रा जिससे rectangle की height दोनों दिशाओं में बढ़ाई जाएगी |

### वापसी मान

विस्तारित rectangle को दर्शाने वाला [Rectangle](../) ऑब्जेक्ट

## संबंधित देखें

* क्लास [Rectangle](../)
* क्लास [Size](../../size/)
* नामस्थान [System::Drawing](../../)
* लाइब्रेरी [Aspose.Slides](../../../)