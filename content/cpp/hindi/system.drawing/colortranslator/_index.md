---
title: ColorTranslator
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "रंग अनुवाद करता है। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन त्रुटियों का कारण बनेगा। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर को तर्क के रूप में फ़ंक्शन्स को पास करने के लिए उपयोग करें।"
type: docs
weight: 66
url: /hi/system.drawing/colortranslator/
---
## ColorTranslator क्लास

रंग अनुवाद करता है। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन त्रुटियों का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को तर्क के रूप में फ़ंक्शन्स को पास करने के लिए उपयोग करें।

```cpp
class ColorTranslator
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | निर्दिष्ट HTML रंग प्रतिनिधित्व को तुल्य [Color](../color/) ऑब्जेक्ट में बदलता है। |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | निर्दिष्ट [Windows](../../system.windows/) रंग को तुल्य [Color](../color/) ऑब्जेक्ट में बदलता है। |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | निर्दिष्ट [Color](../color/) ऑब्जेक्ट को समान HTML रंग की स्ट्रिंग प्रतिनिधित्व में बदलता है। |

## देखें भी

* नामस्थान [System::Drawing](../)
* लाइब्रेरी [Aspose.Slides](../../)