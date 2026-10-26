---
title: LoadingStreamBehavior
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "System::IO::Stream को किसी मेथड को पास किया जाने पर इसे एक Binary Large Object (BLOB) माना जाता है (IBlobManagementOptions description देखें)। इस enumeration के मान यह निर्धारित करते हैं कि System::IO::Stream को मेथड को पास करने पर कैसे ट्रीट किया जाना चाहिए। आवश्यकताओं के आधार पर, सबसे कुशल व्यवहार प्रदान करने के लिए विभिन्न निर्णय लिये जा सकते हैं।"
type: docs
weight: 6735
url: /hi/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

किसी विधि को पास किया गया [System::IO::Stream](../../system.io/stream/) एक Binary Large Object (BLOB) माना जाता है (देखें [IBlobManagementOptions](../iblobmanagementoptions/) description)। इस enumeration के मान यह पहचानते हैं कि [System::IO::Stream](../../system.io/stream/) को विधि को पास करने पर कैसे संभालना चाहिए। आवश्यकताओं के आधार पर, सबसे कुशल व्यवहार प्रदान करने के लिए विभिन्न निर्णय लिये जा सकते हैं।

```cpp
enum class LoadingStreamBehavior
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | स्ट्रीम को अंत तक पढ़ा जाएगा और फिर रिलीज़ कर दिया जाएगा - अर्थात यह सुनिश्चित किया जाएगा कि यह स्ट्रीम भविष्य में [IPresentation](../ipresentation/) इंस्टेंस द्वारा उपयोग नहीं की जाएगी। इसे क्लाइंट कोड द्वारा बंद किया जा सकता है या किसी अन्य तरीके से उपयोग किया जा सकता है। |
| KeepLocked | 1 | स्ट्रीम [IPresentation](../ipresentation/) ऑब्जेक्ट के भीतर लॉक कर दी जाएगी, अर्थात स्ट्रीम का स्वामित्व स्थानांतरित हो जाएगा। [IPresentation](../ipresentation/) ऑब्जेक्ट इस बात के लिए जिम्मेदार होगा कि जब यह ऑब्जेक्ट स्वयं डिस्पोज़ हो जाए तो स्ट्रीम को सही तरीके से डिस्पोज़ किया जाए। यह व्यवहार तब अत्यधिक उपयोगी होता है जब आपको एक बड़े BLOB फ़ाइल (जैसे एक बड़ी वीडियो या ऑडियो - देखें [IBlobManagementOptions](../iblobmanagementoptions/) description) को सीरियलाइज़ करने की आवश्यकता हो और आप इस फ़ाइल को मेमोरी में लोड करने या अन्य प्रदर्शन समस्याओं को रोकना चाहते हों। आप केवल इस फ़ाइल के लिए [System::IO::FileStream](../../system.io/filestream/) खोल सकते हैं और इसे विधि को पास कर सकते हैं, [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior चुनते हुए। |

## देखें

* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)