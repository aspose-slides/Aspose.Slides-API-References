---
title: GetUrl()
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक बाहरी वस्तु के लिए URL लौटाता है। यह मेथड हमेशा तब कॉल किया जाता है जब ILinkEmbedController::GetObjectStoringLocation ने LinkEmbedDecision::Link लौटाया हो और यह तब कॉल किया जा सकता है जब ILinkEmbedController::GetObjectStoringLocation ने LinkEmbedDecision::Embed लौटाया हो लेकिन एम्बेडिंग असंभव है। समान वस्तु id के लिए इसे कई बार कॉल किया जा सकता है।"
type: docs
weight: 14
url: /hi/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) मेथड

एक बाहरी वस्तु के लिए URL लौटाता है। यह मेथड हमेशा तब बुलाया जाता है जब [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) ने [LinkEmbedDecision::Link](../../linkembeddecision/) लौटाया हो और यह तब बुलाया जा सकता है जब [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) ने [LinkEmbedDecision::Embed](../../linkembeddecision/) लौटा हो लेकिन एम्बेडिंग असंभव है। समान वस्तु id के लिए इसे कई बार बुलाया जा सकता है।

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```

### आर्ग्यूमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | **int32_t** | ऑब्जेक्ट id। यह id ऑपरेशन-व्यापी अद्वितीय है। |
| referrer | **int32_t** | रेफ़रर करने वाली वस्तु का id या 0, यदि वस्तु मूल दस्तावेज़ द्वारा रेफ़रर की गई है। रिलेटिव लिंक बनाने के लिए उपयोग किया जा सकता है। |

### रिटर्न वैल्यू

बाहरी वस्तु का URL या null यदि इस वस्तु को अनदेखा किया जाना चाहिए।

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [ILinkEmbedController](../)
* नेमस्पेस [Aspose::Slides::Export](../../)
* लाइब्रेरी [Aspose.Slides](../../../)