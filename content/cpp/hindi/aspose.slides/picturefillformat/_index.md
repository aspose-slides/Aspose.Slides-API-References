---
title: PictureFillFormat
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: चित्र भराव शैली का प्रतिनिधित्व करता है।
type: docs
weight: 4720
url: /hi/aspose.slides/picturefillformat/
---
## PictureFillFormat क्लास

एक चित्र भराव शैली का प्रतिनिधित्व करता है।

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | छवि को आकार को घटाकर, आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है। |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | छवि को आकार को घटाकर, आकार के आकार और निर्दिष्ट रिज़ॉल्यूशन के आधार पर संकुचित करता है। वैकल्पिक रूप से, यह क्रॉप किए गए क्षेत्रों को भी हटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | भरण [Picture](../picture/) के क्रॉप किए गए क्षेत्रों को हटाता है। |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के डबल फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **float** [get_CropBottom](./get_cropbottom/)() override | चित्र के नीचे से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत की संख्या लौटाता है। पढ़ें **float**। |
| **float** [get_CropLeft](./get_cropleft/)() override | चित्र के बाएँ से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत की संख्या लौटाता है। पढ़ें **float**। |
| **float** [get_CropRight](./get_cropright/)() override | चित्र के दाएँ से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत की संख्या लौटाता है। पढ़ें **float**। |
| **float** [get_CropTop](./get_croptop/)() override | चित्र के ऊपर से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत की संख्या लौटाता है। पढ़ें **float**। |
| **int32_t** [get_Dpi](./get_dpi/)() override | चित्र को भरने के लिए उपयोग किए जाने वाले DPI को लौटाता है। पढ़ें **int32_t**। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate वस्तु लौटाता है। केवल-पढ़ने योग्य [IDOMObject](../idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../ipresentationcomponent/) लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../ipresentationcomponent/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | चित्र लौटाता है। केवल-पढ़ने योग्य [ISlidesPicture](../islidespicture/)। |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | चित्र भराव मोड लौटाता है। पढ़ें [Slides::PictureFillMode](../picturefillmode/)। |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | भरण आयत का नीचे का किनारा लौटाता है, जो आकार के बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। पढ़ें **float**। |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | भरण आयत का बायाँ किनारा लौटाता है, जो आकार के बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। पढ़ें **float**। |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | भरण आयत का दायाँ किनारा लौटाता है, जो आकार के बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। पढ़ें **float**। |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | भरण आयत का ऊपर का किनारा लौटाता है, जो आकार के बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित होता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। पढ़ें **float**। |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | टेक्सचर का आकार के भीतर संरेखण कैसे है, यह लौटाता है। यह सेटिंग टेक्सचर पैटर्न के प्रारंभ बिंदु और आकार के भीतर इसकी पुनरावृत्ति को नियंत्रित करती है। पढ़ें [RectangleAlignment](../rectanglealignment/)। |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर उलटता है। पढ़ें [Slides::TileFlip](../tileflip/)। |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | आकार के मूल बिंदु से टेक्सचर का क्षैतिज ऑफ़सेट पॉइंट्स में लौटाता है। सकारात्मक मान टेक्सचर को दाएँ ले जाता है, जबकि नकारात्मक मान बाएँ ले जाता है। पढ़ें **float**। |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | आकार के मूल बिंदु से टेक्सचर का ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में लौटाता है। सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान ऊपर ले जाता है। पढ़ें **float**। |
| **float** [get_TileScaleX](./get_tilescalex/)() override | टेक्सचर भराव के क्षैतिज स्केल को प्रतिशत में लौटाता है। पढ़ें **float**। |
| **float** [get_TileScaleY](./get_tilescaley/)() override | टेक्सचर भराव के ऊर्ध्वाधर स्केल को प्रतिशत में लौटाता है। पढ़ें **float**। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बल्कि नई वस्तु को प्रारंभ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बल्कि नई वस्तु को प्रारंभ करता है और उपवर्गों की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | मूल्‍य प्रकार की वस्तु की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग और nullptr के मामलों के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, स्ट्रिंग्स के मामलों के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | चित्र के नीचे से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत की संख्या निर्धारित करता है। लिखें **float**। |
| void [set_CropLeft](./set_cropleft/)(**float**) override | चित्र के बाएँ से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत की संख्या निर्धारित करता है। लिखें **float**। |
| void [set_CropRight](./set_cropright/)(**float**) override | चित्र के दाएँ से क्रॉप किए गए वास्तविक छवि चौड़ाई के प्रतिशत की संख्या निर्धारित करता है। लिखें **float**। |
| void [set_CropTop](./set_croptop/)(**float**) override | चित्र के ऊपर से क्रॉप किए गए वास्तविक छवि ऊँचाई के प्रतिशत की संख्या निर्धारित करता है। लिखें **float**। |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | चित्र को भरने के लिए उपयोग किए जाने वाले DPI को निर्धारित करता है। लिखें **int32_t**। |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | चित्र भराव मोड को निर्धारित करता है। लिखें [Slides::PictureFillMode](../picturefillmode/)। |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | आकार के बाउंडिंग बॉक्स के नीचे किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भरण आयत के नीचे किनारे को सेट करता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। लिखें **float**। |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | आकार के बाउंडिंग बॉक्स के बाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भरण आयत के बाएँ किनारे को सेट करता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। लिखें **float**। |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | आकार के बाउंडिंग बॉक्स के दाएँ किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भरण आयत के दाएँ किनारे को सेट करता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। लिखें **float**। |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | आकार के बाउंडिंग बॉक्स के ऊपर किनारे से प्रतिशत ऑफ़सेट द्वारा परिभाषित भरण आयत के ऊपर किनारे को सेट करता है। सकारात्मक प्रतिशत एक इनसेट दर्शाता है, जबकि नकारात्मक प्रतिशत एक आउटसेट दर्शाता है। लिखें **float**। |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | आकार के भीतर टेक्सचर का संरेखण कैसे है, इसे सेट करता है। यह सेटिंग टेक्सचर पैटर्न के प्रारंभ बिंदु और आकार के भीतर इसकी पुनरावृत्ति को नियंत्रित करती है। लिखें [RectangleAlignment](../rectanglealignment/)। |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | टेक्सचर टाइल को उसके क्षैतिज, लंबवत या दोनों अक्षों के चारों ओर उलटता है। लिखें [Slides::TileFlip](../tileflip/)। |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | आकार के मूल बिंदु से टेक्सचर का क्षैतिज ऑफ़सेट पॉइंट्स में सेट करता है। सकारात्मक मान टेक्सचर को दाएँ ले जाता है, जबकि नकारात्मक मान बाएँ ले जाता है। लिखें **float**। |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | आकार के मूल बिंदु से टेक्सचर का ऊर्ध्वाधर ऑफ़सेट पॉइंट्स में सेट करता है। सकारात्मक मान टेक्सचर को नीचे ले जाता है, जबकि नकारात्मक मान ऊपर ले जाता है। लिखें **float**। |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | टेक्सचर भराव के क्षैतिज स्केल को प्रतिशत में सेट करता है। लिखें **float**। |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | टेक्सचर भराव के ऊर्ध्वाधर स्केल को प्रतिशत में सेट करता है। लिखें **float**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आन्तरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [PVIObject](../pviobject/)
* क्लास [IPictureFillFormat](../ipicturefillformat/)
* नामस्थान [Aspose::Slides](../)
* लाइब्रेरी [Aspose.Slides](../../)