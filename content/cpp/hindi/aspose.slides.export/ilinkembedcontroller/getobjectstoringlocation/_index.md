---
title: GetObjectStoringLocation()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्धारित करता है कि ऑब्जेक्ट को कहाँ संग्रहीत किया जाना चाहिए। यह विधि प्रत्येक ऑब्जेक्ट आईडी के लिए एक बार कॉल की जाती है। यह गारंटी नहीं है कि समान डेटा, semanticName और contentType वाले दो ऑब्जेक्ट नहीं होंगे, लेकिन अलग-अलग आईडी होंगे।
type: docs
weight: 1
url: /hi/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) विधि


ऑब्जेक्ट को कहाँ संग्रहीत किया जाना चाहिए, यह निर्धारित करता है। यह विधि प्रत्येक ऑब्जेक्ट आईडी के लिए एक बार कॉल की जाती है। यह गारंटी नहीं है कि समान डेटा, semanticName और contentType वाले दो ऑब्जेक्ट नहीं होंगे, लेकिन अलग-अलग आईडी होंगे।

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | **int32_t** | ऑब्जेक्ट आईडी। यह आईडी सहेजने के संचालन में पूरी तरह अद्वितीय है। |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | ऑब्जेक्ट बाइनरी डेटा। यह पैरामीटर null हो सकता है, यदि ऑब्जेक्ट बाइनरी डेटा अभी उत्पन्न नहीं हुआ है। |
| semanticName | [System::String](../../../system/string/) | ऑब्जेक्ट के अर्थ का वर्णन करने वाला एक छोटा पाठ। कंट्रोलर इसे बाहरी ऑब्जेक्ट नाम का हिस्सा के रूप में उपयोग कर सकता है, लेकिन यह डिस्पैचर पर निर्भर करता है कि नाम अद्वितीय हों और केवल अनुमत वर्णों को सम्मिलित करें। |
| contentType | [System::String](../../../system/string/) | ऑब्जेक्ट का MIME प्रकार। |
| recomendedExtension | [System::String](../../../system/string/) | फ़ाइल नाम एक्सटेंशन, जो इस MIME प्रकार के लिए अनुशंसित है। |

### वापसी मान

निर्णय

## संबंधित देखें

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)