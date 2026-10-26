---
title: IPictureFillFormat
second_title: Aspose.Slides for C++ API संदर्भ
description: एक चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
weight: 3225
url: /hi/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat वर्ग

एक चित्र भराव शैली का प्रतिनिधित्व करता है।

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | छवि को आकार घटाकर संपीड़ित करता है, जो आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन पर आधारित है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है। |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | छवि को आकार घटाकर संपीड़ित करता है, जो आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन पर आधारित है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | भरण [Picture](../picture/) के क्रॉप किए गए क्षेत्रों को हटाएँ। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | वास्तविक छवि की ऊँचाई का वह प्रतिशत जो चित्र के नीचे से क्रॉप किया गया है। पढ़ें **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | वास्तविक छवि की चौड़ाई का वह प्रतिशत जो चित्र के बाएँ भाग से क्रॉप किया गया है। पढ़ें **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | वास्तविक छवि की चौड़ाई का वह प्रतिशत जो चित्र के दाएँ भाग से क्रॉप किया गया है। पढ़ें **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | वास्तविक छवि की ऊँचाई का वह प्रतिशत जो चित्र के शीर्ष से क्रॉप किया गया है। पढ़ें **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | चित्र को भरने के लिए उपयोग किया जाने वाला dpi लौटाता है। पढ़ें **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | चित्र लौटाता है। केवल पढ़ने योग्य [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | चित्र भरने का मोड लौटाता है। पढ़ें [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | भरण आयत के निचले किनारे को लौटाता है जो आकार की बाउंडिंग बॉक्स के निचले किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। पढ़ें **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | भरण आयत के बाएँ किनारे को लौटाता है जो आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। पढ़ें **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | भरण आयत के दाएँ किनारे को लौटाता है जो आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। पढ़ें **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | भरण आयत के शीर्ष किनारे को लौटाता है जो आकार की बाउंडिंग बॉक्स के शीर्ष किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। पढ़ें **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | टेक्सचर को आकार के भीतर कैसे संरेखित किया गया है, यह लौटाता है। यह सेटिंग टेक्सचर पैटर्न की प्रारंभिक बिंदु और आकार में इसकी पुनरावृत्ति को नियंत्रित करती है। पढ़ें [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | टेक्सचर टाइल को उसकी क्षैतिज, ऊर्ध्वाधर या दोनों अक्षों के चारों ओर फ़्लिप करता है। पढ़ें [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | टेक्सचर का क्षैतिज ऑफ़सेट, आकार के मूल बिंदु से पॉइंट्स में लौटाता है। सकारात्मक मान टेक्सचर को दाईं ओर ले जाता है, जबकि नकारात्मक मान बाईं ओर। पढ़ें **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | टेक्सचर का ऊर्ध्वाधर ऑफ़सेट, आकार के मूल बिंदु से पॉइंट्स में लौटाता है। सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान ऊपर। पढ़ें **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | टेक्सचर भराव के लिए क्षैतिज स्केल को प्रतिशत में लौटाता है। पढ़ें **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | टेक्सचर भराव के लिए ऊर्ध्वाधर स्केल को प्रतिशत में लौटाता है। पढ़ें **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांच करें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|   [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू प्रकार के ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | चित्र के नीचे से क्रॉप किए गए वास्तविक छवि की ऊँचाई का प्रतिशत सेट करता है। लिखें **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | चित्र के बाएँ भाग से क्रॉप किए गए वास्तविक छवि की चौड़ाई का प्रतिशत सेट करता है। लिखें **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | चित्र के दाएँ भाग से क्रॉप किए गए वास्तविक छवि की चौड़ाई का प्रतिशत सेट करता है। लिखें **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | चित्र के शीर्ष से क्रॉप किए गए वास्तविक छवि की ऊँचाई का प्रतिशत सेट करता है। लिखें **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | चित्र को भरने के लिए उपयोग किए जाने वाले dpi को सेट करता है। लिखें **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | चित्र भरने का मोड सेट करता है। लिखें [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | भरण आयत के निचले किनारे को सेट करता है जो आकार की बाउंडिंग बॉक्स के निचले किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। लिखें **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | भरण आयत के बाएँ किनारे को सेट करता है जो आकार की बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। लिखें **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | भरण आयत के दाएँ किनारे को सेट करता है जो आकार की बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। लिखें **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | भरण आयत के शीर्ष किनारे को सेट करता है जो आकार की बाउंडिंग बॉक्स के शीर्ष किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित है। सकारात्मक प्रतिशत एक इन्सेट को दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट को। लिखें **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | टेक्सचर को आकार के भीतर कैसे संरेखित किया गया है, यह सेट करता है। यह सेटिंग टेक्सचर पैटर्न की प्रारंभिक बिंदु और आकार में इसकी पुनरावृत्ति को नियंत्रित करती है। लिखें [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | टेक्सचर टाइल को उसकी क्षैतिज, ऊर्ध्वाधर या दोनों अक्षों के चारों ओर फ़्लिप करता है। लिखें [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | टेक्सचर का क्षैतिज ऑफ़सेट, आकार के मूल बिंदु से पॉइंट्स में सेट करता है। सकारात्मक मान टेक्सचर को दाईं ओर ले जाता है, जबकि नकारात्मक मान बाईं ओर। लिखें **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | टेक्सचर का ऊर्ध्वाधर ऑफ़सेट, आकार के मूल बिंदु से पॉइंट्स में सेट करता है। सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान ऊपर। लिखें **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | टेक्सचर भराव के लिए क्षैतिज स्केल को प्रतिशत में सेट करता है। लिखें **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | टेक्सचर भराव के लिए ऊर्ध्वाधर स्केल को प्रतिशत में सेट करता है। लिखें **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट तर्क को एक वीक पॉइंटर (साझा नहीं) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [IFillParamSource](../ifillparamsource/)
* नेमस्पेस [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)