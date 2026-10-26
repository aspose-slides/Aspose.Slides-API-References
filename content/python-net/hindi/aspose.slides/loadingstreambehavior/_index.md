---
title: LoadingStreamBehavior enumeration
second_title: Aspose.Slides Python के लिए .NET के माध्यम से API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior एन्यूमरेशन

एक मेथड को पास किया गया **io.RawIOBase** को एक बाइनरी बड़े ऑब्जेक्ट (BLOB) माना जाता है ([`IBlobManagementOptions`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions) विवरण देखें). इस एन्यूमरेशन के मान यह पहचानते हैं कि जब इसे मेथड को पास किया जाए तो **io.RawIOBase** को कैसे ट्रीट किया जाना चाहिए. आवश्यकताओं के आधार पर, सबसे कुशल व्यवहार प्रदान करने के लिए विभिन्न निर्णय लिए जा सकते हैं.

LoadingStreamBehavior प्रकार निम्नलिखित सदस्यों को उजागर करता है:

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| :- | :- |
| READ_STREAM_AND_RELEASE | स्ट्रीम को अंत तक पढ़ा जाएगा और फिर रिलीज़ किया जाएगा - अर्थात यह गारंटी होगी कि यह स्ट्रीम <br/> भविष्य में [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) इंस्टेंस द्वारा उपयोग नहीं की जाएगी. इसे क्लाइंट <br/> कोड द्वारा बंद किया जा सकता है या किसी और तरीके से प्रयोग किया जा सकता है. |
| KEEP_LOCKED | स्ट्रीम को [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) ऑब्जेक्ट के भीतर लॉक किया जाएगा, अर्थात स्ट्रीम की स्वामित्व <br/> स्थानांतरित हो जाएगी. [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation) ऑब्जेक्ट जिम्मेदार होगा <br/> इस स्ट्रीम को सही ढंग से डिस्पोज़ करने के लिए जब यह ऑब्जेक्ट खुद डिस्पोज़ हो जाएगा. <br/> यह व्यवहार अत्यंत उपयोगी है जब आपको एक बड़े BLOB फ़ाइल (जैसे बड़ा <br/> वीडियो या ऑडियो - [`IBlobManagementOptions`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions) विवरण देखें) को सीरियलाइज़ करने की आवश्यकता हो और आप इस फ़ाइल को मेमोरी में लोड होने से रोकना चाहते हों या अन्य प्रदर्शन संबंधी समस्याओं से बचना चाहते हों. आप बस इस फ़ाइल के लिए **System.IO.FileStream** <br/> खोल सकते हैं और इसे एक मेथड को पास कर सकते हैं, [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/hi/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior चुनते हुए. |

### संबंधित देखें
* क्लास [`IBlobManagementOptions`](/slides/python-net/hi/aspose.slides/iblobmanagementoptions)
* क्लास [`IPresentation`](/slides/python-net/hi/aspose.slides/ipresentation)
* मॉड्यूल [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* लाइब्रेरी [`Aspose.Slides`](/slides/python-net)