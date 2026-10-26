---
title: ImageFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: "छवि के फ़ाइल फ़ॉर्मेट का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की कोई भी इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या assertion दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में घेरें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिये करें।"
type: docs
weight: 131
url: /hi/system.drawing.imaging/imageformat/
---
## ImageFormat क्लास

छवि का फ़ाइल फ़ॉर्मेट दर्शाता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की किसी भी इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या assertion त्रुटियाँ उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में घेरें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिये करें।

```cpp
class ImageFormat : public System::Object
```

## विधियां

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | वर्तमान और निर्दिष्ट वस्तुओं द्वारा प्रतिनिधित्व किए गए छवि फ़ॉर्मेट बराबर हैं या नहीं, यह निर्धारित करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो बिटमैप छवि फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो उन्नत मेटाफाइल फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो एक्सचेंजेबल [Image](../../system.drawing/image/) फ़ाइल (Exif) फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो [Graphics](../../system.drawing/graphics/) इंटरचेंज फ़ॉर्मेट (GIF) छवि फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए छवि फ़ॉर्मेट से जुड़े GUID को लौटाता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो [Windows](../../system.windows/) आइकॉन छवि फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो जॉइंट फ़ोटोग्राफ़िक एक्स्पर्ट्स ग्रुप (JPEG) छवि फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो मेमोरी में बिटमैप के फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो W3C पोर्टेबल नेटवर्क [Graphics](../../system.drawing/graphics/) (PNG) छवि फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो टैग्ड [Image](../../system.drawing/image/) फ़ाइल फ़ॉर्मेट (TIFF) छवि फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | एक साझा पॉइंटर लौटाता है जो [ImageFormat](./) ऑब्जेक्ट को दर्शाता है जो [Windows](../../system.windows/) मेटाफाइल (WMF) छवि फ़ॉर्मेट को प्रतिनिधित्व करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | [ImageFormat](./) क्लास का एक इंस्टेंस बनाता है जो निर्दिष्ट GUID से जुड़ी छवि फ़ॉर्मेट को दर्शाता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस प्रतिनिधित्व करता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्टों की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्टों की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंटर (nullptr) के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट तर्क को एक वीक पॉइंटर (साझा के बजाय) सेट करता है। कंटेनर्स में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | इस [ImageFormat](./) ऑब्जेक्ट को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Drawing::Imaging](../)
* लाइब्रेरी [Aspose.Slides](../../)