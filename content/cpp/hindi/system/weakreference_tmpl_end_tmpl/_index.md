---
title: WeakReference<>
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक weak रेफ़रेंस का प्रतिनिधित्व करता है, जो एक ऑब्जेक्ट को रेफ़रेंस करता है जबकि उस ऑब्जेक्ट को हटाने की अनुमति देता है।
type: docs
weight: 1522
url: /hi/system/weakreference_tmpl_end_tmpl/
---
## WeakReference<> क्लास

एक weak रेफ़रेंस का प्रतिनिधित्व करता है, जो एक ऑब्जेक्ट को रेफ़रेंस करता है जबकि उस ऑब्जेक्ट को हटाने की अनुमति देता है।

```cpp
class WeakReference<> : public WeakReference<System::Object>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| **bool** [get_IsAlive](./get_isalive/)() const | यह बताता है कि वर्तमान WeakReference ऑब्जेक्ट द्वारा रेफ़रेंस किया गया ऑब्जेक्ट हटाया गया है या नहीं। |
| const [WeakPtr](../weakptr/)\<[Object](../object/)\>\& [get_Target](./get_target/)() const | वर्तमान WeakReference ऑब्जेक्ट द्वारा रेफ़रेंस किया गया ऑब्जेक्ट (लक्ष्य) प्राप्त करता है। |
| void [set_Target](./set_target/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | वर्तमान WeakReference ऑब्जेक्ट द्वारा रेफ़रेंस किया गया ऑब्जेक्ट (लक्ष्य) सेट करता है। |
| [WeakReference](./weakreference/)() | डिफ़ॉल्ट कंस्ट्रक्टर। |
| [WeakReference](./weakreference/)(std::nullptr_t) | nullptr से कंस्ट्रक्टर। |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | एक नया WeakReference क्लास का इंस्टेंस प्रारंभ करता है, जो निर्दिष्ट ऑब्जेक्ट को रेफ़रेंस करता है। |
| [WeakReference](./weakreference/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | एक नया WeakReference क्लास का इंस्टेंस प्रारंभ करता है, जो निर्दिष्ट ऑब्जेक्ट को रेफ़रेंस करता है। |

## संबंधित देखें

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)